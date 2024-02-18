# zombie_accounts_detection
Zombie account (churned) reactivation -- The development phase continues locally and will be uploaded when completed.

Problem Statement

Many online services experience user churn, leaving behind "zombie accounts"—inactive user profiles with occasional, small transactions. This project aims to develop a predictive model that identifies zombie accounts and suggests the most effective re-engagement strategies.

Methodology

1. Data Collection and Preparation
    a. Synthetic Data Generation: I'll Employ the Synthetic Data Vault (SDV) library to generate realistic synthetic transaction data based on the structure and correlations within the existing dataset. (https://www.kaggle.com/datasets/shivamb/bank-customer-segmentation/data) The dataset captures user transactions, timestamps, account registration dates, and profile/demographic information (if available).
2. Exploratory Data Analysis (EDA)
3. Defining  "Zombie Accounts"
4. Modeling
   Baseline: Starting with simple classification models (e.g., Logistic Regression, Decision Trees, Random Forest) to establish a performance benchmark.
   Advanced Models: Investigating the combining LSTM outputs with features derived from traditional machine learning models for potential performance gains.

![image](https://github.com/Eserhimas/zombie_accounts_detection/assets/27355212/b021316a-e518-4461-a0a6-c9fb280c30d7)

