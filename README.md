# Customer Churn Prediction

## Project Overview
Built a machine learning model to predict telecom customer churn using Logistic Regression and Random Forest.

## Dataset
Telco Customer Churn Dataset  
7043 customer records, 21 features

## Data Preprocessing
- Converted TotalCharges to numeric
- Handled missing values
- Removed customerID
- Applied one-hot encoding
- Converted target variable to binary

## Models Used
- Logistic Regression (~78% accuracy)
- Random Forest (~78% accuracy)

## Key Insights
- Customers with higher monthly charges and shorter tenure are more likely to churn.
- Pricing and contract type significantly influence churn behavior.

## Tools
Python, Pandas, Scikit-learn, Matplotlib
