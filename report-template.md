# Module 12 Report Template

## Overview of the Analysis

The purpose of this analyis was to help identify whether a borrower would be a high-risk or a low-risk borrower.

The Logistic Regession model was used in this analysis to predict the loan risk. The analysis took multiple variables into consideration when making its predictions.

* The purpose of the analysis was to predict whether the loan in question would be a heathly loan ("0") or a high-risk loan ("1").
* The variables that were taking into consideratiion were:
    - loan size	
    - interest rate	
    - borrower income
    - debt to income
    - num of accounts
    - derogatory marks
    - total debt
    - loan status

* Based on these variables variables we want the model to be able to learn and predict whether the loan will be heathly or high risk.

* The stages used in this process was"
    - Processing Data (reading csv file)
    - creating label sets for X and y 
    - Training Data (train_test_split)
    - Logistic Regression (with fitting it into the model)
    - Predictions
    - Creating confusin matrix
    - Creating classification report

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
