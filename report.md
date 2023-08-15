# Module 12 Report Template

## Overview of the Analysis


The purpose of this analysis is to train and evaluate models with imbalanced classes using historical lending activity to identify the creditworthiness of borrowers.
the financial data provided showed customers' loan details(X variable) and current loan status(y variable). After importing the required libaries and reading in the csv file, I assigned the X and y variables mentioned previously and checked the balance of each variables. I then split the data into training and test datatsets using the train_test_split function. Next, i fit the regression model using the training data and used the test data with the fitted model to generate predictions. I did the same using the Oversampled training data using the RandomOversampler module and compared the results. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  The Logistic Regression Model with imbalanced data had an accuracy score of 95%
  Precision = 100% for health loans, 85% for high risk loans, 99% average
  Recall = 99% for health loans, 91% for high risk loans. 99% average



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  TheLogistic Regression Model with oversampled training data had an accuracy score of 99%
  Precision = 100% for healthy loans, 84% for high risk loans, 99% average
  Recall = 99% for health loans, 99% for hish risk loans, 99% average

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
The oversampled model saw both an increase in its accuracy score, recall, and f1 scores specifically for higher risk loans with a small decrease in precision for higher risk loans. While the averages for each metric remained mostly unchanged, due to the improvements in the recall and f1 scores, between the 2 models I would recommend the oversampled model.

