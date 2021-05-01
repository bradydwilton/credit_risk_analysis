# Credit Risk Analysis

## Overview of the Analysis

The following analysis tests several oversamping, undersampling, and combination sampling techniques with logistic regression analysis, as well as two ensemble techniques, to determine which machine learning model performs best at predicting credit risk using real-world data provided by LendingClub.

## Results

### Random Oversampling and Logistic Regression
* Accuracy Score: __0.598__
* Precision: __0.99__
* Recall: __0.62__
* F1 Score: __0.76__
* Classification Report:
<img src='https://github.com/bradydwilton/credit_risk_analysis/blob/main/images/ros_classification_report.png'>

### SMOTE Oversampling and Logistic Regression
* Accuracy Score: __0.628__
* Precision: __0.99__
* Recall: __0.65__
* F1 Score: __0.78__
* Classification Report:
<img src='https://github.com/bradydwilton/credit_risk_analysis/blob/main/images/smote_classification_report.png'>

### Cluster Centroids Undersampling and Logistic Regression
* Accuracy Score: __0.556__
* Precision: __0.99__
* Recall: __0.42__
* F1 Score: __0.59__
* Classification Report:
<img src='https://github.com/bradydwilton/credit_risk_analysis/blob/main/images/cc_classification_report.png'>

### SMOTEENN Combination Sampling and Logistic Regression
* Accuracy Score: __0.629__
* Precision: __0.99__
* Recall: __0.59__
* F1 Score: __0.74__
* Classification Report:
<img src='https://github.com/bradydwilton/credit_risk_analysis/blob/main/images/smoteenn_classification_report.png'>

### Balanced Random Forest Classifier
* Accuracy Score: __0.661__
* Precision: __0.99__
* Recall: __1.00__
* F1 Score: __1.00__
* Classification Report:
<img src='https://github.com/bradydwilton/credit_risk_analysis/blob/main/images/rf_classification_report.png'>

### Easy Ensemble AdaBoost Classifier
* Accuracy Score: __0.901__
* Precision: __0.99__
* Recall: __0.95__
* F1 Score: __0.97__
* Classification Report:
<img src='https://github.com/bradydwilton/credit_risk_analysis/blob/main/images/eec_classification_report.png'>

## Summary

For the six machine learning models that were tested in this credit risk analysis, five had accuracy scores below 0.67. Of those five, only the Balanced Random Forest Classifier had an F1 score above 0.8. There was one model, however, which had a much higher accuracy score of 0.9. This was the Easy Ensemble Classifier model, which was also close to the highest F1 score, coming in at 0.97. For these reasons, the Easy Ensemble Classifier model is the clear choice for predicting credit risk for LendingClub and has the sensitivity and accuracy needed to be recommended for the job.