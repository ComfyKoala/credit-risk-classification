# Credit Risk Classification

## Overview of the Analysis

The goal of this analysis was to evaluate the Supervised ML model in predicting healthy vs high-risk loans based on:

- loan size
- interest rate
- borrower's income
- debt to income ratio
- number of financial accounts
- derogatory marks
- total debt
  I used the Logistic Regression model because this is a binary classification (i.e healthy vs high-risk)

## Results

- When predicting healthy loans, the model has:
  - 100% precision (no false positives)
  - 99% recall (very small portion of false negatives)
- When predicting high-risk loans, the model has:
  - 85% precision (15% false positive rate)
  - 91% recall (9% false negative rate)
