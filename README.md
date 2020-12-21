# Sepsis-prediction
To predict the development of sepsis in patients entering the ICU

## Data
Kaggle data for Sepsis prediction.
Data is given in two folders - training set A and B.
Training set A has 20,336 patient files and set B has 20,000.
Each patient file is a csv with a time series information of their vitals and their demographics and a flag for when the Sepsis develops if it develops

## Implementation
We train non-temporal models that utilizes logistic regression, decision trees, gradient and xgboost. We compare the performance of these models and choose the appropriate one depending on the data available for analysis
