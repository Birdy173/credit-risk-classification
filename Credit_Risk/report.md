
# Credit Risk Report

## Overview of the Analysis

The purpose of this analysis was to assess and compare the performance of machine learning models in predicting loan repayment outcomes based on financial and borrower information. The data included variables such as loan amount, interest rate, term, and employment length, and the target variable, `loan_status`, indicated whether a loan was fully paid (0) or defaulted/charged off (1). 

The analysis followed these stages of the machine learning process:
1. Feature and label separation: Isolating `loan_status` as the target variable and the remaining columns as features.
2. Model training and evaluation: Using algorithms like Logistic Regression and others to build models and evaluate their performance.
3. Metrics analysis: Reviewing accuracy, precision, recall, and F1-scores to assess model effectiveness.

The primary goal was to identify the model that best predicts loan defaults (class `1`), as accurate detection of this class is crucial for financial risk management.

---

## Results

* **Machine Learning Model 1 (Logistic Regression)**:
    - **Accuracy**: 99%
    - **Precision**: 
        - Class `0`: 1.00
        - Class `1`: 0.86
    - **Recall**: 
        - Class `0`: 0.99
        - Class `1`: 0.94
    - **F1-Score**: 
        - Class `0`: 1.00
        - Class `1`: 0.89

---

## Summary

Based on the results:

- The Logistic Regression model performed exceptionally well with an overall accuracy of 99%. It showed nearly perfect precision and recall for predicting `0` (fully paid loans) and strong metrics for predicting `1` (defaults/charged off loans).
- The **recall** for class `1` is especially important because identifying loan defaults is a critical task for financial institutions. The model’s recall of 94% for this class means it correctly identifies the vast majority of defaults.

### Recommendation

I recommend using the Logistic Regression model for this task. It provides a strong balance between precision and recall, and its high recall for class `1` makes it suitable for minimizing the risk of missed loan defaults. If identifying false positives (loans incorrectly predicted as defaults) is less critical, this model is an excellent choice for the problem at hand.
