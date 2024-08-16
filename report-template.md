## Overview of the Analysis

The purpose of this analyis was to help identify whether a borrower would be a high-risk or a low-risk borrower.

The Logistic Regession model was used in this analysis to predict the loan risk for borrowers. The analysis took multiple variables into consideration when making its predictions.

* Loans were classified into two categories: heathly loans ("0") or a high-risk loans ("1").
* The variables that were taking into consideratiion were:
    - loan size	
    - interest rate	
    - borrower income
    - debt to income
    - num of accounts
    - derogatory marks
    - total debt
    - loan status

* Based on these variables we wanted the model to be able to learn and predict whether the loan will be heathly or high-risk.

* The stages used in this process were:
    - Processing Data (reading csv file)
    - Creating label sets for X and y 
    - Training Data (train_test_split)
    - Logistic Regression (with fitting it into the model)
    - Predictions
    - Creating confusin matrix
    - Creating classification report
    - Analysis of model findings

## Results

Accuracy scores: the precision, recall and F-1 scores of all machine learning models are as followed.

* **Healthy Loans ("0")**:
    - Precision: 1.00
    - Recall: 0.99
    - F-1: 1.00

* **High-Risk Loans ("1")**:
    - Precision: 0.85
    - Recall: 0.91
    - F-1: 0.88

**Model Accuracy**: 0.99

## Summary

In summary the model was able to predict the classificatios of loans well with a higher accuracy for healthy loans but still above average for high-risk loans. 

The model to predict healthly loans performs best because of the preciscion, recall and f1-scores being nearly perfect. There is a larger margin of error for the higher risk loans which is why this one is not the best performing model. 

I would recommend this model with assistance for classification of loan borrowers. However, for the higher-risk loans I would recommend a seceond pair of eyes (non-AI) review to make a final decsion due to the slightly larger margin of error the model throws of to help protect the Lender make a final decision.