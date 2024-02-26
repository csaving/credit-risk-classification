# credit-risk-classification

## Overview of the Analysis

* I will  use various techniques to train and evaluate a model based on loan risk. 
* I'm using a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.
* I am trying to predict 'loan status'. A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.
* Steps taken:
    * Imported the data from a csv file into pandas dataframe. 
    * Created the labels set (`y`)  from the “loan_status” column, and then created the features (`X`) DataFrame from the remaining columns.
    * Split data in to training and testing sets. 
    * Fit a logistic regression model by using the training data (`X_train` and `y_train`).
    * Saved the predictions on the testing data labels by using the testing feature data (`X_test`) and the fitted model.
    * Evaluated the model’s performance by generating a confusion matrix and printing classification report. 

* The method I used was `LogisticRegression`.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    *              precision    recall  f1-score   support

    *       0       1.00      0.99      1.00     18765
    *       1       0.85      0.91      0.88       619

    *    accuracy                           0.99     19384
    *   macro avg       0.92      0.95      0.94     19384
    *   weighted avg       0.99      0.99      0.99     19384


## Summary

**Question:** How well does the logistic regression model predict both the `0` (healthy loan) and `1` (high-risk loan) labels?

**Answer:** The model was excellent at predicting 'healthly loan'. The results were still decent with predicting high-risk loans. 


