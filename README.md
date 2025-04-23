# Impaye Prediction - Insurance Default Risk Modeling

This project aims to predict which insured clients are at risk of missing payments based on their contract and demographic data. The work was done using real-world insurance datasets, anonymized for demonstration purposes.

---

## Project Overview
- **Objective**: Build a machine learning pipeline to predict potential defaults in insurance payments
- **Context**: Developed at ECA Assurances as part of internal data science efforts
- **Outcome**: Developed a final model achieving 71% precision in predicting payment defaults.

---

##  Dataset
- Merged multiple internal tables: contract information and client demographic details
- Preprocessing includes:
  - Cleaning inconsistent fields
  - Merging datasets by keys (CONTRAT)
  - Handling missing values and outliers
  - Feature selection (VIF)

---

## Machine Learning Pipeline
- **Resampling**:
  - SMOTE
  - ADASYN
  - RandomUnderSampler

- **Models Used**:
  - LightGBM
  - Random Forest

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
- `pretraitement.ipynb`: Merging datasets, data cleaning, feature selection, feature engineering
- `train.ipynb`: Model training, feature selection, evaluation, interpretation

---

## Tech Stack
- Python
- pandas, numpy, scikit-learn, imbalanced-learn
- LightGBM

---

## Author
**Chihoon Lee**  
Data Scientist @ ECA Assurances, Lyon, France  
Contact: chihoon.lee94@gmail.com  
GitHub: [github.com/chihoonlee](https://github.com/chihoonlee)

---


