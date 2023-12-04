# Module 20 Credit Risk Classification Report 

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of this analysis was to see how logistical regression can predic the credit risk of potential lenders. The target value for analysis is loan_status. All other features in csv file were used to predict target. Value_counts helps us see the size of the data set before splitting it up into a training and a testing set. Logistical regression model is used for classification problems with binary values (i.e. healthy (0), high risk(1)).
  

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  * Accuracy = 99% based on testing of data set
  * Precision = 100% for prediciton of 'healthy loans' within the test data of 18765 records. 85% precision of high risk loans with test data of only 619 records.
  * Recall = 99% for healthy loans. Recall = 91% for high risk loans. This means that the model is more accurate at recording true positives for healthy loans rather than high risk loans.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  * Machine Learning Model 2 is omitted per Brett Payne. Per Joanna: 
  Brett mentioned in the instructor/TA channels the "Predict a Logistic Regression Model with Resampled Training Data" section in the notebook is not required. It used to be taught in this class but isn't anymore.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

* Model 1:
Logistic Regression model had a precision of 100% on the prediction of healthy loans while having a precision of 85% for the high risk loans. This is also visible when looking at the recall and f1-scores which also have lower values related to high risk loans. 15% of the loans that were predicted to be high risk loans were actually healthy loans. The precision of the model can be enhanced with more data. Having such a small sample of high risk loan

If you do not recommend any of the models, please justify your reasoning.
