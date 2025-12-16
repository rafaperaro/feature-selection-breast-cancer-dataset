# Feature Selection with KBest and LASSO

## Objective
The goal of this project was to use feature selection techniques, KBest, LASSO and Decision Tree and to identify
the most important features on the Breast Cancer dataset that would help predicting wether a tumor is belign or malign.

## Dataset
- [Breast Cancer Wisconsin Dataset](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)
- 30 numerical features describing tumor characteristics
- Binary target:
  - 0: Malignant
  - 1: Benign

## Approach
- Data cleaning and standardization
- Exploratory Data Analysis (univariate, bivariate, and multivariate)
- Outlier removal (≤ 5% of observations)
- Feature selection using:
  - KBest (chi-square test)
  - LASSO regression
  - Decision tree feature importance
- Model evaluation using Accuracy and F1 Score

## Key Insight
Feature selection, particularly LASSO, significantly improves performance
and model simplicity when working with high-dimensional and highly correlated
clinical data.

## Tools
- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
