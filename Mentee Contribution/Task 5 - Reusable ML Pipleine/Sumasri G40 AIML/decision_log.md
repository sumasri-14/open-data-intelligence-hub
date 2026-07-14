# Decision Log

## Objective

Develop a reusable machine learning pipeline for customer churn prediction.

---

## Model Selection

Selected Model:
Random Forest Classifier

Reason:

- Handles both numerical and categorical data effectively.
- Provides good performance without extensive tuning.
- Robust against overfitting.
- Easy to integrate into a scikit-learn pipeline.

---

## Missing Value Strategy

Numerical Features:
Median Imputation

Reason:

Median is less sensitive to outliers than mean.

Categorical Features:
Most Frequent Imputation

Reason:

Maintains the most common category for missing values.

---

## Feature Encoding

Technique Used:

One-Hot Encoding

Reason:

Machine learning models require numerical input, and One-Hot Encoding efficiently converts categorical variables into numerical form.

---

## Feature Scaling

Technique Used:

StandardScaler

Reason:

Standardizes numerical features and improves model performance.

---

## Pipeline Design

Pipeline Components:

1. Data Preprocessing
2. Feature Encoding
3. Feature Scaling
4. Random Forest Classifier

This structure ensures preprocessing is automatically applied during prediction.

---

## Model Saving

Library Used:

Joblib

Reason:

Efficient serialization of large machine learning models.

---

## Conclusion

Using a reusable pipeline improves reproducibility, consistency, and simplifies deployment for future predictions.