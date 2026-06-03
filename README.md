# Bank Customer Churn Prediction

## Project Overview

This project analyzes customer churn behavior using a bank customer dataset and develops machine learning models to predict whether a customer is likely to leave the bank.

The analysis combines exploratory data analysis (EDA), data visualization, and predictive modeling to identify key churn drivers and evaluate model performance.

---

## Objectives

* Analyze customer characteristics associated with churn
* Identify key factors influencing customer retention
* Build predictive models to forecast customer churn
* Compare machine learning algorithms and evaluate performance
* Generate business recommendations to reduce customer attrition

---

## Dataset

Source: Kaggle Bank Customer Churn Dataset

Dataset contains customer information including:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Account Balance
* Number of Products
* Credit Card Ownership
* Active Membership Status
* Estimated Salary
* Churn Status (Target Variable)

---

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Project Workflow

### 1. Data Exploration and Cleaning

* Examined dataset structure
* Checked for missing values
* Verified data types
* Prepared features for analysis

### 2. Exploratory Data Analysis (EDA)

Analyzed:

* Overall churn rate
* Churn rate by country
* Churn rate by gender
* Churn rate by active membership status
* Customer demographic profiles
* Balance and age distributions

### 3. Data Visualization

Created visualizations including:

* Age distribution by churn status
* Balance distribution by churn status
* Churn rate by country
* Churn rate by gender

### 4. Predictive Modeling

Implemented and compared:

#### Logistic Regression

Performance:

* Accuracy: 81.6%
* Precision: 60%
* Recall: 19%
* F1 Score: 0.29

#### Random Forest Classifier

Performance:

* Accuracy: 86.45%
* Precision: 75%
* Recall: 47%
* F1 Score: 0.57

---

## Key Findings

### 1. Older Customers Are More Likely to Churn

Customers who left the bank tend to be older than retained customers.

### 2. Higher Balance Customers Show Greater Churn Risk

Customers with larger account balances exhibited higher churn rates.

### 3. Germany Has the Highest Churn Rate

German customers demonstrated significantly higher churn rates compared with customers from France and Spain.

### 4. Female Customers Have Higher Churn Rates

Female customers showed noticeably higher churn rates than male customers.

### 5. Random Forest Outperformed Logistic Regression

Random Forest achieved:

* Higher overall accuracy
* Better recall
* Stronger ability to identify churned customers

---

## Business Recommendations

Based on the analysis, the bank should focus retention strategies on:

* Older customers
* High-balance customers
* German customer segments
* Female customer groups

Targeted retention campaigns and proactive customer engagement may help reduce future churn.

---

## Repository Structure

```text
bank-customer-churn-analysis/
│
├── README.md
├── customer-churn-analysis.ipynb
└── Bank Customer Churn Prediction.csv
```

---

## Future Improvements

* Hyperparameter tuning
* Feature engineering
* Handling class imbalance using SMOTE
* XGBoost implementation
* Model deployment with Streamlit
