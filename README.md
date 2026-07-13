# Task-Level Features Show No Detectable Risk Signal in a Public Construction Dataset: A Diagnostic Audit

Reproducible analysis code for the paper of the same name.

## Contents
- `construction_risk_analysis.ipynb` — full analysis; regenerates every number in the paper in a single run
- `construction_dataset.csv` — dataset (Kaggle, CC0 Public Domain)

## Reproducing
Open the notebook in Google Colab and run all cells. Upload the CSV when prompted.
Fixed random seed (42) throughout. Runtime approximately 10 minutes.

## What the analysis covers
Feature–label correlation · model training (Logistic Regression, Random Forest, XGBoost) · class weighting · 5-fold cross-validation · hyperparameter search (accuracy and macro-F1 scoring) · gain-based and permutation feature importance · feature engineering · error analysis · Wilson confidence intervals · McNemar tests against a majority-class baseline · label permutation test (1,000 shuffles) · positive control with sensitivity sweep

## Environment
Python 3.12 · scikit-learn · XGBoost · statsmodels · matplotlib · pandas · numpy

## Data source
Python Developer, "Construction Project Management Dataset," Kaggle, 2023.  
https://www.kaggle.com/datasets/programmer3/construction-project-management-dataset  
Licensed CC0 Public Domain.

## License
MIT
