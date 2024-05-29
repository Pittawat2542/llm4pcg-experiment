# Towards LLM4PCG: A Preliminary Evaluation of Open-Weights Large Language Models Beyond ChatGPT4PCG

This repository contains the code and datasets for the paper "Towards LLM4PCG: A Preliminary Evaluation of Open-Weights Large Language Models Beyond ChatGPT4PCG" accepted at [IEEE CoG 2024](https://2024.ieee-cog.org).

## Authors
Pittawat Taveekitworachai, Yi Xia, Pratch Suntichaikul, Ruck Thawonmas

## Abstract

This paper presents the second ChatGPT4PCG competition at the 2024 IEEE Conference on Games. In this edition of the competition, we follow the first edition, but make several improvements and changes. We introduce a new evaluation metric along with allowing a more flexible format for participants' submissions and making several improvements to the evaluation pipeline. Continuing from the first edition, we aim to foster and explore the realm of prompt engineering (PE) for procedural content generation (PCG). While the first competition saw success, it was hindered by various limitations; we aim to mitigate these limitations in this edition. We introduce diversity as a new metric to discourage submissions aimed at producing repetitive structures. Furthermore, we allow submission of a Python program instead of a prompt text file for greater flexibility in implementing advanced PE approaches, which may require control flow, including conditions and iterations. We also make several improvements to the evaluation pipeline with a better classifier for similarity evaluation and better-performing function signatures. We thoroughly evaluate the effectiveness of the new metric and the improved classifier. Additionally, we perform an ablation study to select a function signature to instruct ChatGPT for level generation. Finally, we provide implementation examples of various PE techniques in Python and evaluate their preliminary performance. We hope this competition serves as a resource and platform for learning about PE and PCG in general.

## File structure
```
.
├── __init__.py
├── prompts
│   ├── 0.txt
│   └── 1.txt
└── zero_shot_multi_turn.py
```

## Installation and Usage
0. Create a virtual environment (if needed):
```bash
conda create -n llm4pcg python=3.12
```
and activate it:
```bash
conda activate llm4pcg
```
1. Install the requirements:
```bash
pip install -r requirements.txt
```
2. Run the code to generate responses as needed.
