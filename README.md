
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

The **Random Forest model** achieved an **AUC score of 0.817**, indicating superior discriminative power and stability across various classification thresholds. Its smoother ROC curve suggests consistent performance, making it a robust ch
- The **Random Forest model** achieved an **AUC score of 0.817**, indicating superior discriminative power and stability across various classification thresholds. Its smoother ROC curve suggests consistent performance, making it a robust choice for this predictive task.
  
- The **Logistic Regression model**, while performing decently with an AUC score of **0.78**, showed more fluctuations in its ROC curve, which suggests greater sensitivity to certain decision thresholds.

- **Hyperparameter Tuning**: During the **Random Search CV** and **Grid Search CV** processes, the Random Forest model was further optimized, which led to improvements in its performance. Random Search CV allowed for broader exploration, identifying promising parameters faster, while Grid Search CV refined the search, exhaustively evaluating all combinations within the hyperparameter grids.

### Recommendations for Customer Retention:

1. **Targeted Marketing**: Focus on retention efforts for **older customers** and those with **fewer products**. Since Age and Product Count are significant features, these customers might need additional incentives or engagement to stay.

2. **Personalized Offers**: Create tailored offers for customers based on their **credit score**, and **estimated salary**. High-value customers with low churn probability should be rewarded with loyalty programs.

3. **Enhanced Customer Experience**: Prioritize enhancing the experience for **active members** and **long-tenure customers**. These groups are more likely to remain loyal, so focusing on engagement can further reduce churn.

4. **Product Bundling**: Bundle products to increase **customer value**. Offering multiple products could improve loyalty, particularly among customers with high balance-to-salary ratios.

5. **Financial Incentives**: Offer **discounts**, **rewards**, or **loyalty programs** to retain high-value customers, particularly those with high credit scores or balances.

6. **Customer Segmentation**: Segment customers based on features such as **age**, **tenure**, and **product usage**. By creating targeted retention strategies, you can focus efforts where they are most needed.
