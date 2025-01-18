# Module 12 Report Template

## Overview of the Analysis

This analysis aimed to develop a machine learning model (Logistic Regression Model) to predict loan risk for a financial 
institution. 

The dataset contained various financial attributes of loans, including loan size, interest rate, borrower income, 
debt-to-income ratio, number of accounts, derogatory marks, and total debt. The primary goal was to predict loan_status, 
i.e.,whether a 
loan would be classified as healthy (0) or high-risk (1).


The analysis involved the following steps:
Data preprocessing and exploration
Splitting the data into training and testing sets
Creating and training a Logistic Regression model
Evaluating the model's performance using confusion matrix and classification report
Write a Credit Risk Analysis Report



## Results

The Logistic Regression model's performance:
Accuracy: 99.26%
Healthy Loans (0):
Precision: 99.80%
Recall: 99.43%
High-Risk Loans (1):
Precision: 84.46%
Recall: 94.03%


## Summary

Summarise the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

The Logistic Regression model demonstrates excellent performance in predicting both healthy and high-risk loans. 
With an overall accuracy of 99.26%, 
it shows strong capability in distinguishing between the two loan types.
The model excels at identifying healthy loans, with near-perfect precision and recall. For high-risk loans, 
while the performance is slightly lower, 
it still maintains a high level of accuracy, especially in terms of recall.
Recommendation: This model is highly recommended for use by the company for the following reasons:
High overall accuracy (99.26%)
Excellent performance in identifying healthy loans (99.80% precision, 99.43% recall)
Strong capability in detecting high-risk loans (84.46% precision, 94.03% recall)
The high recall for high-risk loans (94.03%) is particularly valuable, as it minimizes the chance of misclassifying 
a high-risk loan as healthy
The model's balanced performance across both loan types makes it a reliable tool for loan risk assessment. 
However, if the cost of misclassifying 
a high-risk loan as healthy is significantly higher than the reverse, 
the company might consider further optimizing the model to improve precision 
for high-risk loans, possibly at the expense of slightly lower recall.