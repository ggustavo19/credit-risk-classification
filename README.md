# Credit Risk Analysis Report

## Overview of the Analysis
The purpose of the analysis was to develop a predictive model to accurately forecast whether a borrower will default on a loan. The financial data was on the following: Loan size, interest rate, borrower income, debt to income, number of accounts held by borrower, deragatory marks on credit history, and total debt. With all of this criteria/data we needed to predict whether the borrower would pay the loan back `0` or at some point default `1`. The primary method used in this predictive model was `Logistic Regression`

## Results

* Logitic Regression Model:
    * ![image](https://github.com/ggustavo19/credit-risk-classification/assets/152371383/79b94e8f-1cbd-45be-aee7-1f69c017152c)
    * Accuracy: The model achieved an overall accuracy of 99%, indicating that it correctly predicted the loan status for 99% of the dataset.
    * Precision:
      * `0` (No Default): The precision for predicting non-defaults is 100%.
      * `1` (Default): The precision for predicting defaults is 85%, indicating that 85% of the loans predicted to default actually defaulted.
    * Recall:
      * `0` (No Default): The recall for non-defaults is 99%. The model identified 99% of all actual non-defaults correctly.
      * `1` (Default): The recall for defaults is 91%. The model identified 91% of all actual defaults correctly.
    * F1-Score:
      * `0` (No Default): The F1-score for non-defaults is 1.00, calculating the average between precision and recall.
      * `1` (Default): The F1-score for defaults is 0.88, calculating the average between precision and recall.
    * Support:
      * `0` (No Default): The model was tested on 18,765 borrowers that did not default.
      * `1` (Default): The model was tested on 619 borrowers that defaulted.
  
## Summary

Summarize the results of the machine learning model.
