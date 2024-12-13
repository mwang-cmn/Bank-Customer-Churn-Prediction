
# Bank Customer Churn Prediction Analysis

This project involves analyzing customer data from a bank to predict churn using machine learning models. The dataset includes demographic, financial, and engagement attributes of customers, enabling insights into factors influencing their decision to stay or exit. The analysis was conducted in Google Colab.
The Data used in this project can be found [here](https://mavenanalytics.io/data-playground)

[View Notebook](https://github.com/mwang-cmn/Bank-Customer-Churn-Prediction/blob/main/Banking_Churn_Prediction.ipynb)

## Problem Statement
Fit a model that will classify customers who will churn and those who are retained.
### Objectives
- **Predict Customer Churn**: Develop models to identify customers at risk of leaving the bank.
- **Feature Importance Analysis**: Determine key features driving churn.
- **Model Comparison**: Evaluate the performance of Logistic Regression and Random Forest classifiers.

### Key Findings
- **Model Performance**: The Random Forest classifier outperformed Logistic Regression with an AUC of 0.87, indicating stronger predictive power.
- **Top Predictors**: *Age*, *Number of Products*, and *Balance* emerged as the most significant features influencing churn.
- **Recommendations**: Implement targeted retention strategies for at-risk segments based on age, product ownership, and engagement levels.

### Tools Used
- **Python**, **scikit-learn** for modeling
- **Random Search CV** and **Grid Search CV** for hyperparameter tuning
- **Matplotlib**, **Seaborn** for data visualization

This project showcases the process of data preprocessing, model training, hyperparameter tuning, and evaluation to deliver actionable insights for customer retention.
