# Customer Churn Prediction

## Overview

This project predicts whether a customer is likely to churn (leave a telecom service) using supervised machine learning classification algorithms. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and comparison of multiple classification models.

---

## Dataset

* **Dataset:** Telco Customer Churn Dataset
* **Source:** IBM Sample Dataset / Kaggle
* **Records:** 7,032 customers
* **Target Variable:** `Churn`

---

## Project Workflow

* Data Loading
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Encoding
* Train-Test Split
* Feature Scaling
* Model Training
* Model Evaluation
* Feature Importance Analysis
* Model Comparison

---

## Machine Learning Models

The following models were implemented and compared:

* Logistic Regression
* Random Forest Classifier
* XGBoost Classifier

---

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

---

## Results

| Model               | Accuracy   | Precision  | Recall     | F1 Score   | ROC-AUC   |
| ------------------- | ---------- | ---------- | ---------- | ---------- | --------- |
| Logistic Regression | **80.38%** | **64.76%** | **57.49%** | **60.91%** | **0.836** |
| Random Forest       | 79.46%     | 64.12%     | 51.60%     | 57.19%     | 0.835     |
| XGBoost             | 78.04%     | 60.00%     | 52.14%     | 55.79%     | 0.830     |

**Best Performing Model:** Logistic Regression

---

## Key Insights

* Contract type was the most influential feature affecting customer churn.
* Customers with one-year and two-year contracts were significantly less likely to churn.
* Tenure, Monthly Charges, Internet Service, and Payment Method also played important roles in predicting churn.
* Logistic Regression outperformed the more complex ensemble models on this dataset, indicating that the customer churn patterns were effectively captured by a linear decision boundary.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* XGBoost
* Jupyter Notebook

---


