# README

## Author

Meropi Maria Lampropoulou

## Overview
This project compares two transformer adaptation strategies for the Natural Language Inference (NLI) task:
Supervised fine-tuning of RoBERTa-base
Zero-shot and few-shot prompting with LLaMA-3-8B-Instruct

The study evaluates performance, computational cost, and output stability across approaches.

NLI is formulated as a three-class classification problem (entailment, contradiction, neutral), where the goal is to determine the semantic relationship between a premise and a hypothesis.


## Versions
Python : 3.12.12
Torch: 12.6
Datasets: 4.3.0
Transformers: 4.57.3
Evaluate version: 0.4.6
NumPy version: 2.3.3
tqdm version: 4.67.1


## Runtime
Designed to run in Google Colab with GPU support. Runtime for LampropoulouM_fine_tuning.ipynb was approx. 1hr, while for LampropoulouM_prompting.ipynb was approx. 10mins.

