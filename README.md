# Regression Tree Algorithm

This repository contains a Python implementation of a Regression Tree algorithm using scikit-learn library.

## Introduction

Regression Tree is a machine learning algorithm used for solving regression problems. It works by recursively splitting the dataset into subsets based on the feature that results in the best split. This process is repeated until a stopping criterion is met, such as reaching a maximum depth, or if further splitting does not improve the model significantly.

## Usage

To use the Regression Tree algorithm, you can follow these steps:

1. Prepare your dataset: Make sure your dataset is in the appropriate format for regression tasks. Ensure that it is cleaned and preprocessed as necessary.

2. Import the RegressionTree class:

```python
from regression_tree import RegressionTree
