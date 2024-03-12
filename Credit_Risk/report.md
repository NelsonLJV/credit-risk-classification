# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

I believe the purpose of this analysis was to create machine learning models that would help us predict loan risk based on other financial data that were provided. Said data included: loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The variable we aimed to predict was the loan status, which had two categories: a healthy loan(0) and a high-risk loan(1). The stages of the machine learning are data loading, data prep, model training, model evaluating, and prediction making. For this testing we used the logistic regression model.

## Results

The model demonstrated:

Perfect precision (1.00) for predicting healthy loans 
High precision (0.87) for predicting high-risk loans
Perfect recall for healthy loans (1.00) 
High recall for high-risk loans (0.89)
High F1-score for healthy loans (1.00)
High F1-score for high-risk loans (0.88), 


Overall, model 1 demonstrates strong predictive performance for both healthy and high-risk loans based on the provided evaluation metrics.

## Summary

Our logistic regression model was exceptionally accurate and precise in its predictions. Healthy Loans (0) precision and recall are both at 100%, indicating perfectly accurate predictions for this label. High-Risk Loan (1) in the other hand had a precision score of 0.87, and a recall score of 0.89, demonstrating quite high accuracy in predicting said high-risk loans. 
---------------------------
