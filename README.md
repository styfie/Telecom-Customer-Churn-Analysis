# 📊 Telecom Customer Churn Analysis

### Exploratory Data Analysis & Feature Engineering

## 📌 Project Overview

Customer churn is a critical challenge in the telecom industry. This project focuses on **analyzing customer behavior and identifying key factors influencing churn** through detailed Exploratory Data Analysis (EDA) and robust Feature Engineering techniques.
## 🎯 Objectives

* Understand customer demographics and service usage patterns
* Identify key drivers of customer churn
* Perform feature extraction and feature selection to enhance model performance

## 📂 Dataset

Dataset available on the Kaggle platform **Telecom Customer Churn dataset**. This dataset includes a variety of variables that represent customer profiles and behaviors, forming the basis for predicting the likelihood of
churn.

## 🔍 Exploratory Data Analysis (EDA) + Data Visualization

* Analysis of churn distribution across customer segments
* Visualization of relationships between churn and key variables
* Detection of trends and correlations

## ⚙️ Data Preprocessing

* Encoding categorical variables
* Scaling numerical features

## 🛠 Feature Engineering

### 🔹 Feature Extraction

Several new features were created to better capture customer behavior:
* Tenure_in_years: Converted customer tenure from months to years for easier interpretation of subscription duration.
* ChargesRatio: Ratio of Total Charges to Monthly Charges, providing insight into how long a customer has been using the service based on spending patterns.
* LevelTotalCharges: Categorized Total Charges into spending levels (Low, Medium, High) to segment customers based on overall spending.
* LevelTenure: Grouped customer tenure into categories such as New, Mid-Term, and Long-Term to simplify analysis of subscription length.

### 🔹 Feature Selection

* Correlation analysis to remove redundant features
* Statistical tests to evaluate feature significance
* Reduced dimensionality while preserving predictive power

## 📈 Key Insights

* Long-term contracts significantly reduce churn risk
* Customers with higher monthly charges and shorter tenure are more likely to churn
* Value-added services play a critical role in customer retention

## 🚀 Outcome

* A refined dataset ready for machine learning models
* Clear understanding of churn-driving factors
* Actionable insights to support customer retention strategies

## 🧰 Tools & Technologies

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

## 📎 Next Steps

* Build and evaluate machine learning models for churn prediction
* Perform hyperparameter tuning and model optimization
* Deploy insights through dashboards or APIs
