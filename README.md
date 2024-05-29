# Towards LLM4PCG: A Preliminary Evaluation of Open-Weights Large Language Models Beyond ChatGPT4PCG

This repository contains the code and datasets for the paper "Towards LLM4PCG: A Preliminary Evaluation of Open-Weights Large Language Models Beyond ChatGPT4PCG" accepted at [IEEE CoG 2024](https://2024.ieee-cog.org).

## Authors
Pittawat Taveekitworachai, Yi Xia, Pratch Suntichaikul, Ruck Thawonmas

## Abstract

This paper presents an initial step towards general evaluations of open-weight large language models (LLMs) using the ChatGPT4PCG platform, a Science Birds level generation challenge designed to evaluate LLMs on the complex task of generating stable, English-character-resembling, and diverse levels. While ChatGPT4PCG competitions have their own merit in providing a comprehensive platform for evaluating ChatGPT on complex tasks, the competitions focus solely on ChatGPT is rather limiting considering the fact that there are many available choices of open-weight LLMs. We report 13 LLMs from five model families of various properties in their design choices and sizes to evaluate on a modified ChatGPT4PCG 2 competition platform. We observe that the scaling law holds in general, but the inherent capabilities of LLMs due to their pre-training and architecture choices also play an equal role. We open-source the modification of the ChatGPT4PCG platform to support future research on evaluating LLMs in this area.

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
