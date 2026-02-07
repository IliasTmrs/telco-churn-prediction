# Telco Customer Churn Prediction

This project focuses on predicting customer churn using the IBM Telco Customer Churn dataset.  
The goal is to identify customers at high risk of leaving and understand the key factors driving churn.

---

## 📌 Project Overview

- Business problem: Predict customer churn in a telecom company
- Dataset: IBM Telco Customer Churn (Kaggle)
- Target variable: `Churn`
- Models used:
  - Logistic Regression
  - Random Forest

---

## 📂 Project Structure

```text
telco-churn-prediction/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_preprocessing.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   └── 03_modeling_and_evaluation.ipynb
│
├── outputs/
│   └── figures/
│       ├── churn_distribution.png
│       ├── roc_curve.png
│       └── feature_importance.png
│
└── README.md
