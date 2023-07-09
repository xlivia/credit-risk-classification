# Module 20 Credit Risk Classification Report

## Overview of the Analysis
In this analysis, we used logistic regression models to classify credit risk based on financial information. The purpose of the analysis was to predict loan status (healthy loan or high-risk loan) using features such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, and derogatory marks. The data was split into training and testing sets, and the models were evaluated based on their accuracy, precision, and recall scores.

## Results
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.
- Machine Learning Model 1 (Logistic Regression with Original Data):
  - Balanced Accuracy Score: 0.9520
  - Precision Score: 0.85
  - Recall Score: 0.91
- Machine Learning Model 2 (Logistic Regression with Resampled Data):
  - Balanced Accuracy Score: 0.9936
  - Precision Score: 0.99
  - Recall Score: 0.99

## Summary
Based on the results, both machine learning models performed well in predicting credit risk. However, the logistic regression model with resampled data achieved higher accuracy, precision, and recall scores compared to the model with original data. The model with resampled data showed improved performance in identifying both healthy loans and high-risk loans.

In credit risk classification, it is crucial to correctly identify high-risk loans (label '1') to minimize potential losses. Therefore, the model with higher recall (Model 2) is recommended as it achieved a recall score of 0.99 for high-risk loans, indicating that it correctly identified a significant portion of these loans. While the model with original data (Model 1) also performed well, it had a lower recall score of 0.91 for high-risk loans.

Considering the higher performance of the resampled model in correctly identifying high-risk loans, we recommend using the logistic regression model with resampled data for credit risk classification tasks.