# Reusable Customer Churn Prediction Pipeline

## Project Overview

This project demonstrates how to build a reusable machine learning pipeline using scikit-learn for predicting customer churn.

The pipeline automates the complete machine learning workflow including data preprocessing, feature engineering, model training, evaluation, serialization, and prediction.

## Dataset

Dataset Used:
WA_Fn-UseC_-Telco-Customer-Churn.csv

Target Variable:
Churn

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib

## Pipeline Components

The pipeline performs:

- Missing value handling
- Numerical feature scaling
- One-Hot Encoding for categorical features
- Random Forest Classification

## Model Evaluation

Evaluation metrics used:

- Accuracy
- Confusion Matrix
- Classification Report

## Output Files

- customer_churn_pipeline.ipynb
- customer_churn_pipeline.pkl
- decision_log.md
- model_evaluation_report.md
- README.md

## Conclusion

The reusable pipeline ensures that identical preprocessing steps are applied during both training and prediction, improving consistency and reducing manual preprocessing errors.