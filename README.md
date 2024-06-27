# Code Smell-Guided Prompting for LLM-Based Defect Prediction in Ansible Scripts

## Overview
This repository contains the code and datasets used for the experiments presented in our paper titled "Exploring Code Smell-Guided Prompting for LLM-Based Defect Prediction in Ansible Scripts". The purpose of this repository is to ensure the reproducibility of our experiments and provide transparency for our research methods.

## Repository Structure
```
├── test_dataset
│ ├── 1
│ │ ├── clean
│ │ └── defect
│ ├── 2
│ │ ├── clean
│ │ └── defect
│ ├── 3
│ │ ├── clean
│ │ └── defect
│ ├── ...
│ ├── 29
│ │ ├── clean
│ │ └── defect
│ ├── 30
│ │ ├── clean
│ │ └── defect
├── test_results
│ ├── gemini
│ ├── gpt3_5
│ ├── gpt4_0
├── gemini.ipynb
├── gpt.ipynb
├── requirements.txt
└── README.md
```

## Main Components

There are three main components of this repository:

1. **Test Dataset**: Contains 30 pairs of Ansible defect and clean code obtained from GHPR crawling. In total, it includes 60 Ansible scripts (half are defect codes and the other half are clean codes).

2. **LLM Query Experiment Codes**: Consists of two versions, GPT (3.5 or 4.0) and Gemini. Note that you need to modify the `api_key` in each code to run it.

3. **Result Data**: Contains the test results of our research. Each text file is named following the format `label_prompting_method_result.txt`. Each nth row in a text file corresponds to the result of the nth data in the test dataset.

## Prerequisites
- Python 3.8 or higher

## Getting started
Once you have cloned this repository, install all the packages for this project.
```
git clone https://github.com/HyunsunHong/CSP_for_LLM-based-SDP-in-Ansible.git
pip install -r requirements.txt
```

## Run the experiment
```
something
```
