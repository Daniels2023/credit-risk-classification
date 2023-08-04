# Supervised Machine Learning Report - Loan Analysis


## Overview of the Analysis

The primary objective of this Supervised Machine Learning (SML) report is to predict loans as either healthy or high-risk based on the provided dataset. Financial features such as loan size, borrower income, and interest rate were selected as relevant inputs for the model. The selected machine learning model for this task is Logistic Regression, which is proficient at predicting binary outcomes. In this case, each data point is assigned a score of 0 for a healthy loan prediction or 1 for a high-risk loan prediction.

The implementation of the prediction involves training and testing a Logistic Regression model using the Scikit-Learn library.


## Results

The confusion matrix results yielded the following outcomes:

* True Negative: 18,679 (Accurate 'no-risk' predictions)

* False Positive: 80 (Incorrect 'high-risk' predictions)

* False Negative: 67 (Incorrect 'no-risk' predictions)

* True Positive: 558 (Accurate 'high-risk' predictions)


The Logistic Regression model demonstrated the following metrics:

* Precision of 100% for healthy loans

* Recall of 100% for healthy loans

* Precision of 87% for high-risk loans

* Recall of 89% for high-risk loans

* Overall ML Accuracy of 99%


## Summary

The outcomes from the confusion matrix demonstrate that the majority of data points are classified as "True Negative" and "True Positive," with a smaller number categorized as "False Positive" and "False Negative".

In conclusion, Logistic Regression proved to be an effective tool for identifying healthy loans within the dataset with utmost precision. However, caution is advised when utilizing this model for predicting high-risk loans due to its less than 100% accuracy rate.