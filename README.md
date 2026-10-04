# Loan Approval Classification

## Project Overview

This project uses Machine Learning to predict whether a loan application will be approved or rejected.

The dataset contains information about loan applicants, including income, age, education, credit score, loan amount, loan intent, and previous loan defaults.

## Dataset

* Number of records: 44,993 after data cleaning
* Number of features: 13
* Target variable: `loan_status`
* `0` = Rejected
* `1` = Approved

## Data Preprocessing

The following preprocessing steps were performed:

* Checked the dataset structure and data types.
* Checked for missing values.
* Removed unrealistic age values greater than 100.
* Split the data into training and testing sets.
* Used stratified sampling to preserve the target distribution.
* Applied One-Hot Encoding to categorical features.

## Exploratory Data Analysis

Several visualizations were created to understand the data, including:

* Age Distribution
* Income Distribution by Loan Status
* Credit Score Distribution by Loan Status
* Loan Approval Rate by Loan Intent
* Loan Approval Rate by Previous Loan Defaults

## Machine Learning Models

Two classification algorithms were trained:

1. Logistic Regression
2. Random Forest Classifier

## Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

Because the target classes are imbalanced, F1-Score was considered an important metric when comparing the models.

## Feature Importance

Feature importance was analyzed using the Random Forest model to identify the variables that contributed most to the loan approval predictions.

## Tools and Libraries

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Google Colab
* GitHub

## Conclusion

The project demonstrates a complete Machine Learning classification workflo
