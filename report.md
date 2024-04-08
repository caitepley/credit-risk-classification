# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to explore different aspects of loans (interest rate, how many accounts the borrower has in total, borrower income, etc.) in order to predict if a loan is considered high risk or not. To perform this analysis, the dataset was split into labels and features, where the labels were the loan-status (healthy or high-risk) and the features were all of the other available information about the loan and its borrower. This was then split into training and testing data, where one chunk was used to train the logistic regression algorithm and the other chunk was used to test it. The testing included generating label values for the features and then comparing the results to the labels that came with the dataset initially.

## Results

- accuracy scores: the accuracy of the model better for healthy loans than for high-risk loans. This means that the model is more likely to falsely identify a high-risk loan as healthy rather than the other way around.
- precision: the precision for healthy loans was higher than that for high-risk loans (100% vs. 85%). This means that the model is better at predicting healthy loans rather than high-risk loans.
- recall: the recall for healthy loans was also higher than that for high-risk loans (99% vs 91%). This means that the model is better at finding healthy loans rather than high-risk loans. It also means that the model is more likely to classify a high-risk loan as a healthy loan than it is to missclassify a healthy loan. 

## Summary

The logistic regression machine learning model can predict healthy loans very accurately. However, it cannot predict high-risk loans as accurately, meaning that some high-risk loans may be falsely classified as healthy. This model should not be used as the sole source for determining if a loan is high-risk or not, but it is accurate enough that it could be used to supplement other classification sources. 

If the model were to be implemented as the sole source for determining if a loan was high-risk, then the lender would need to be aware that they would be loaning money to some people who could be considered a liability and may not be able to pay off all of their loan(s).


