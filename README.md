# credit-risk-classification

# Report

## Overview of the Analysis

The dataset included features related to loan applicants, and the target variable was the loan status (healthy or high-risk).
Used Logistic Regression as the classification algorithm.
Split the data into training and testing sets.
Evaluated the model's performance using balanced accuracy, confusion matrix, and classification report.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
Balanced Accuracy Score: 0.95
Precision (Label 1): 0.86
Recall (Label 1): 0.91

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
Balanced Accuracy Score (Resampled): 0.99
Precision (Label 1): 0.85
Recall (Label 1): 0.99

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

The model with resampled data (Model 2) outperforms the original model, especially in recall for high-risk loans (label 1). The context of credit risk analysis often emphasizes correctly identifying high-risk loans to minimize potential losses. Therefore, the higher recall in Model 2 is crucial.