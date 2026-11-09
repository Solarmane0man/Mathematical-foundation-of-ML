# Multi-layer Perceptron — Mini Project

**Author:** Abdellah BENSALEM

## Overview

Implementation of a one-hidden-layer neural network from scratch in pure Python (no deep learning libraries), applied to two datasets: a synthetic moons dataset and the MNIST digits dataset.

## Requirements

```
numpy
scikit-learn
matplotlib
```

Install with:
```bash
pip install numpy scikit-learn matplotlib
```

## How to run

Open the notebook in Jupyter:
```bash
jupyter notebook MLP_mini-project_Abdellah_BENSALEM.ipynb
```

Run all cells in order.

## Contents

| Section | Description |
|---|---|
| Q1–Q4 | Dataset exploration, manual linear classifier |
| Q5–Q6 | Logistic regression baseline, limits of linear models |
| Q7–Q12 | Neural network implementation (init, forward pass, backprop, training) |
| Q13 | Effect of number of epochs on moons and MNIST |
| Q14 | Train/validation split, hyperparameter search, overfitting demonstration |
| Q15 (bonus) | NumPy vectorisation, mini-batch SGD, weight decay, deeper networks |

## Key results

- Best linear model (logistic regression): ~86% accuracy on moons
- MLP with 10 hidden neurons, 200 epochs: ~96% on moons
- MLP with 20 hidden neurons, 100 epochs: ~97.5% on MNIST
- Best hyperparameters found (Q14 grid search): hidden=40, lr=0.001 → 88.9% validation accuracy on MNIST in 30 epochs
