# Credit Card Customer Churn Analysis

## Overview
End-to-end churn prediction pipeline on 10,127 bank customers (BankChurners dataset).

## Methods
- Exploratory data analysis across demographics (age, gender, income, education)
- Class imbalance handling via SMOTE (84/16 split)
- Logistic Regression (ROC-AUC: 0.9053)
- Random Forest Classifier (ROC-AUC: 0.9828)

## Key Findings
- Churn is driven by behavioral signals, not demographics. Top predictors: total transaction count, transaction amount, and revolving balance.
- Churned customers average ~45 fewer transactions and 45% lower utilization than retained customers.

## Stack
Python, Pandas, scikit-learn, imbalanced-learn, Matplotlib, Seaborn
