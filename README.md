# Credit Risk Analysis

## Overview of the Analysis

The following analysis tests several oversamping, undersampling, and combination sampling techniques with logistic regression analysis, as well as two ensemble techniques, to determine which machine learning model performs best at predicting credit risk using real-world data provided by LendingClub.

## Results


### Definitions Included in Results:
* Balanced Accuracy Score
* Precision
* Recall (Sensitivity)

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