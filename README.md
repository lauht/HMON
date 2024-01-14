# PA-HMON

This is a PyTorch implementation of the paper "Prompt-Adaptive Hyper-Message Overflow Networks: Enhancing Stock Movement Prediction by Mitigating Information Asymmetry".

## Requirements
* python==3.7.13
* torch==1.8.0

## News
News headlines are collected from [Benzinga](https://github.com/Benzinga/benzinga-python-client).

## How to train the model
1. Run `MPA.ipynb`.
This script would pre-train the HMON through the movement prompt adaptation strategy.
2. Run `PA-HMON.ipynb`.
This script would build an HMON model, and then fine-tune it.
