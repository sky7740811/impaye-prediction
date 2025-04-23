# Impaye Prediction - Insurance Default Risk Modeling

This project aims to predict which insured clients are at risk of missing payments ("impayés") based on their contract and demographic data. The work was done using real-world insurance datasets, anonymized for demonstration purposes.

---

## Project Overview
- **Objective**: Build a machine learning pipeline to predict potential defaults in insurance payments
- **Context**: Developed at ECA Assurances as part of internal data science efforts
- **Outcome**: Increased recall on critical classes by 8%, improved model transparency

---

##  Dataset
- Merged multiple internal tables: contract information and client demographic details
- Preprocessing includes:
  - Cleaning inconsistent fields
  - Merging datasets by keys (e.g., PERIODE, CONTRAT)
  - Handling missing values and outliers
  - Feature selection (Boruta, VIF)

---

## Machine Learning Pipeline
- **Resampling**:
  - SMOTE
  - ADASYN
  - RandomUnderSampler

- **Models Used**:
  - LightGBM
  - Random Forest
  - SVM

- **Evaluation**:
  - Train/test split
  - F1-score, Recall, Confusion Matrix
  - Hyperparameter optimization using TPE
  - Model explainability using ELI5

---

## Visualizations
- Correlation matrices
- Distribution plots
- Model performance charts (Precision-Recall curves, Confusion Matrices)

---

## Project Files
- `clean_new.ipynb`: Data cleaning, EDA, merging datasets
- `train.ipynb`: Model training, evaluation, and interpretation

---

## ⚖Tech Stack
- Python
- pandas, numpy, scikit-learn, imbalanced-learn
- LightGBM, TensorFlow/Keras (not used here but part of author’s stack)
- Power BI (used for internal dashboards, not in notebook)

---

## Author
**Chihoon Lee**  
Data Scientist @ ECA Assurances, Lyon, France  
Contact: chihoon.lee94@gmail.com  
GitHub: [github.com/chihoonlee](https://github.com/chihoonlee)

---

> This project reflects personal work and experience from real-world business cases, anonymized and shared for educational and professional showcase purposes.

