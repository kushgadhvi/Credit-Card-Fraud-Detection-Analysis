# Credit Card Transactions Analysis

## Overview
This repository contains Jupyter Notebooks for analyzing credit card transactions, detecting fraud, and performing statistical analysis. The dataset used is `credit_card_transactions_trim.csv`, which contains transaction details for analysis. You can also run the code on the full dataset available on Kaggle: [Credit Card Transactions Dataset](https://www.kaggle.com/datasets/priyamchoksi/credit-card-transactions-dataset). The trim version provided here is a smaller subset of the same dataset for quick analysis.

## Files Description

### 1. Credit_Card_Transactions_Analysis.ipynb
- Performs initial data exploration and cleaning.
- Generates descriptive statistics and visualizations.
- Identifies trends and patterns in transaction data.

### 2. Fraud_Detection_Analysis.ipynb
- Applies statistical tests and machine learning techniques for fraud detection.
- Analyzes transaction anomalies and behavior patterns.
- Uses hypothesis testing to determine fraudulent activity.

### 3. Statistical_Analysis_Credit_Cards.ipynb
- Conducts deep statistical analysis on transaction data.
- Utilizes chi-square tests, t-tests, and correlation analysis.
- Provides insights into customer spending behavior.

## Dataset: credit_card_transactions_trim.csv
- This dataset contains trimmed credit card transaction records used for analysis.
- Fields include transaction amount, location, merchant, fraud status, and timestamps.
- The `is_fraud` column is the target variable, indicating whether a transaction is fraudulent (1) or not (0).

## How to Use
1. Install necessary dependencies: `pip install pandas numpy matplotlib seaborn scipy`
2. Run the notebooks in Jupyter Notebook or JupyterLab.
3. Load `credit_card_transactions_trim.csv` in the same directory as the notebooks.

## Acknowledgments
This analysis was conducted as part of an independent research project on financial transactions and fraud detection.
