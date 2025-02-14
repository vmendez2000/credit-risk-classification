# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to assess the risk of loans using machine learning models, specifically logistic regression. The dataset contained financial information about loan applicants, with the goal of predicting whether a loan would be classified as high-risk (1) or healthy (0).

The dataset included multiple financial variables, and the primary target variable was loan_status. A value of 0 indicated a healthy loan, while a value of 1 indicated a high-risk loan. The stages of the machine learning process included:

* Loading and exploring the dataset.
* Splitting the data into features (X) and labels (y).
* Dividing the dataset into training and testing sets.
* Training a logistic regression model.
* Evaluating the model's performance using a confusion matrix and classification report.

The logistic regression algorithm was selected due to its effectiveness in binary classification problems and its interpretability in financial risk assessment.

## Results

### Machine Learning Model: Logistic Regression
    * Accuracy Score: 0.99
    * Precision Score: 1.00 (for healthy loans), 0.87 (for high-risk loans)
    * Recall Score: 1.00 (for healthy loans), 0.95 (for high-risk loans)
    

## Summary

The logistic regression model provided insights into loan risk classification. Based on the results:

* The model's accuracy score of 99% suggests it is highly reliable.
* The precision score indicates that the model is very accurate in predicting healthy loans but slightly less so for high-risk loans.
* The recall score of 95% for high-risk loans suggests the model correctly identifies most high-risk cases.

If the recall score for high-risk loans is low, the model may not be effective for financial institutions needing to minimize risk exposure. If the precision is low, it may misclassify too many loans as high-risk, affecting approvals.

Recommendation: The logistic regression model is recommended due to its high accuracy and strong performance in identifying high-risk loans. However, financial institutions should assess the trade-off between precision and recall before full implementation.
