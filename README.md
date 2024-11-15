# credit-risk-classification
## Overview

This project focuses on building machine learning models to predict loan repayment outcomes. Using financial and borrower information, we aim to classify loans as either fully paid or defaulted/charged off.

## Dataset

The dataset includes the following features:
- **Loan Amount**: The principal loan amount issued.
- **Interest Rate**: The annual interest rate applied to the loan.
- **Term**: The duration of the loan (e.g., 36 months or 60 months).
- **Employment Length**: The borrower's employment tenure in years.
- **Loan Status**: The target variable, indicating whether the loan is fully paid (0) or defaulted/charged off (1).

## Objectives

1. Preprocess the dataset to prepare it for machine learning.
2. Train and evaluate models to classify loan repayment outcomes.
3. Compare the performance of various machine learning models using metrics such as accuracy, precision, recall, and F1-score.

## Machine Learning Models

- **Logistic Regression**: Evaluated for its simplicity and efficiency in binary classification.
- Additional models may be explored for comparison.

## Results

The Logistic Regression model achieved the following results:
- **Accuracy**: 99%
- **Precision**: 
  - Fully Paid (Class 0): 1.00
  - Defaulted/Charged Off (Class 1): 0.86
- **Recall**: 
  - Fully Paid (Class 0): 0.99
  - Defaulted/Charged Off (Class 1): 0.94
- **F1-Score**: 
  - Fully Paid (Class 0): 1.00
  - Defaulted/Charged Off (Class 1): 0.89

## Recommendation

The Logistic Regression model is recommended due to its high accuracy and strong recall for predicting loan defaults, making it effective for minimizing financial risk.

## How to Use

1. Clone the repository.
2. Install the required dependencies (`pip install -r resources/requirements.txt`).
3. Run the `credit_risk_classification.ipynb` script to train and evaluate the models.
