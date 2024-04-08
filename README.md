# credit-risk-classification

The purpose of this analysis was to explore different aspects of loans (interest rate, how many accounts the borrower has in total, borrower income, etc.) in order to predict if a loan is considered high risk or not. To perform this analysis, the dataset was split into labels and features, where the labels were the loan-status (healthy or high-risk) and the features were all of the other available information about the loan and its borrower. This was then split into training and testing data, where one chunk was used to train the logistic regression algorithm and the other chunk was used to test it. The testing included generating label values for the features and then comparing the results to the labels that came with the dataset initially.

The results of the analysis are available in the 'report.md' file.

## To Run
Python needs to be installed on the local machine. The Jupyter notebook can either be ran cell-by-cell or as a whole to produce the results.

## References
- information on the meaning of the classification report stats: https://medium.com/@kohlishivam5522/understanding-a-classification-report-for-your-machine-learning-model-88815e2ce397 