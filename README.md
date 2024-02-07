# credit-risk-classification


## Overview of the Analysis

In this activity, the goal was to import a csv file containing information on loan applications, and train a model to determine whether or not a loan is high risk based on the details of each loan, including loan size, interest rate, the borrower's income, their debt to income ratio, their number of accounts, amount of total debt, and their number of derogatory marks on their credit history. First, we removed the column indicating whether the loan was high risk. Next, we split the data into training and testing datasets using train_test_split. Once these sets were created, we created a logistic regression model and passed the training data sets through it to train the model. Next, we passed the test data through the trained model, generated a confusion matrix on the expected versus actual results, and obtained the accuracy scores of the model.

## Results

After training and testing, the model had the following results.
    * The model was 100% accurate in predicting healthy loans, having 100% scores in precision, recall, and accuracy
    * The model was 88% accurate in predicting high risk loans, having 87% score in precision, 89% in recall, and 88% in accuracy
    * Overall, the model was 99% accurate in predicting whether a loan was health or high risk.

## Summary

This model was entirely effective at predicting if a loan was healthy. However, mistakes were made when trying to predict high risk loans, which only 88% were correctly identified. On a grand scale, the model incorrectly predicted just 147 out of the 19384 loans in the test data set, a failure rate of less than one percent. Overall, I can recommend this model's ability to identify healthy loans, however companies should consult their margins and policies to determine if an 88% accuracy score on high risk loans is acceptable.