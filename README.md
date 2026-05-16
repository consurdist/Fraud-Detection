# Fraud Detection

Credit card fraud detection using logistic regression on the 
IEEE-CIS Fraud Detection dataset, built as part of Siraj Raval's 
Machine Learning MasterClass, September 2019.

## Approach

Transaction and identity datasets merged on TransactionID. EDA 
with Seaborn to explore fraud patterns by transaction amount and 
email domain. Columns with >50% null values dropped. Remaining 
nulls filled with -999 sentinel. Categorical columns encoded via 
LabelEncoder before fitting. Logistic regression via scikit-learn.

Notable finding: anonymous.com email domain showed no meaningful 
correlation with fraud. Gmail dominated fraud volume but proportionally 
to its overall prevalence.

## Stack

Python, pandas, scikit-learn, seaborn, Kaggle API

## Status

Completed for bootcamp submission, September 2019. Not maintained.
