# Cook County Housing Price Prediction

UC Berkeley Data 100 | Spring 2026

## Overview
End-to-end predictive modeling pipeline on 500,000+ Cook County
property records to predict home sale prices and analyze equity
implications in property tax assessments.

## What I built
- EDA on 500,000+ records across 61 variables
- Data cleaning: missing value imputation, outlier removal,
  log transformation of target variable
- Engineered 12+ features for improved predictive performance
- Trained linear regression on 204,792 observations
- Applied k-fold cross-validation — reduced RMSE by 18% over baseline
- Designed a custom equity-aware error metric to detect
  disparate impact across income-stratified geographic clusters

## Key Results
- RMSE reduced 18% over baseline
- Custom fairness metric surfaced systemic bias patterns
  in property tax assessments

## Stack
Python · Pandas · NumPy · scikit-learn · Matplotlib · Seaborn · Jupyter Notebook
