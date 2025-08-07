# Fairness with Residual Gates in Neural Networks

This project explores how residual gates affect fairness and accuracy in binary classification using the Adult Income dataset. 

## Goals

- Compare fairness metrics of standard MLP vs gated MLP
- Use IBM AIF360 for fairness evaluation
- Aim for reproducible, conference-quality results

## Dataset

- UCI Adult Income dataset
- Preprocessed using pandas
- Fairness metrics computed using AIF360

## Models

- MLP (baseline)
- GatedMLP (our residual gate architecture)

## Metrics

- Accuracy
- Statistical Parity Difference
- Disparate Impact
- Mean Difference

## Setup

```bash
pip install -r requirements.txt
