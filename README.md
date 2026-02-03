# Home Credit Default Risk — MSCI 546 Project

This repository contains our **MSCI 546 (Advanced Machine Learning)** team project for the **Home Credit Default Risk** Kaggle competition. The objective is to predict the probability that a loan applicant will experience repayment difficulty using historical application and financial data.

## Project Overview
- **Task:** Supervised binary classification (default vs. no default)
- **Dataset:** Home Credit Default Risk (Kaggle)
- **Primary Metric:** ROC-AUC
- **Baseline Model:** Logistic Regression with robust preprocessing
- **Extensions:** Feature aggregation from relational tables and neural network-based models

## Key Components
- **EDA:** Class imbalance analysis, missingness profiling, anomaly detection (`DAYS_EMPLOYED` sentinel), and univariate signal exploration (`EXT_SOURCE_2`)
- **Preprocessing:** Median imputation + scaling for numerical features; most-frequent imputation + one-hot encoding for categorical features
- **Validation:** 5-fold stratified cross-validation
- **Baseline Performance:** Mean ROC-AUC ≈ **0.7465**

## Reproducibility
All experiments are fully reproducible using the provided notebooks.  
Data can be downloaded directly from Kaggle:
https://www.kaggle.com/competitions/home-credit-default-risk

## Team
- Ben Fogerty  
- Shailleze Mahenrenathan  
- Sneh Shah  
- Dev Shah  
- Sher Verma
