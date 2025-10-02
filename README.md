Sales & Customer Behaviour Analysis
📌 Overview

This project explores sales and customer behaviour data to identify the key drivers of sales performance and segment customers into distinct groups. The goal is to support data-driven decision-making in retail and e-commerce — from optimising marketing spend to improving customer retention.

🎯 Objectives

Clean and prepare raw sales/customer datasets.

Identify patterns and anomalies in customer behaviour.

Build predictive models to assess sales drivers and customer churn risk.

Use clustering (K-Means) to segment customers for targeted campaigns.

Provide actionable recommendations for marketing, sales, and retention strategy.

🛠️ Tools & Libraries

Python: Pandas, NumPy, Scikit-learn

Visualisation: Matplotlib, Seaborn

Models: Decision Tree Classifier, K-Means Clustering

📊 Key Steps & Methods

Data Wrangling

Removed duplicates and outliers.

Cleaned variables (Credit Score, Income, Marketing Spend, Loan Amount, etc.).

Exploratory Data Analysis (EDA)

Uncovered customer purchase frequency patterns.

Analysed correlations between income, spending score, and loan behaviour.

Modelling

Decision Tree → identified feature importance (e.g. Marketing Spend, Loan Amount).

K-Means Clustering → segmented customers into distinct groups for marketing.

Results

Forecast accuracy and churn prediction.

Clear customer segments with different income/spending profiles.

💡 Business Insights

Marketing Spend & Loan Amount are major drivers of sales outcomes.

Customer Segmentation supports tailored loyalty programs and targeted promotions.

Models can guide optimised resource allocation and reduce churn.

📂 Repository Contents

Sales_Customer_Segmentation_Analysis_MD.ipynb → Main analysis notebook.

cleaned_without_outliers.csv → Preprocessed dataset.

Visual outputs (plots of feature importance, clusters).

🚀 Next Steps

Extend analysis with time-series forecasting (ARIMA, SARIMAX).

Build an interactive dashboard in Power BI/Tableau using results.

Apply model evaluation metrics (F1, ROC-AUC) for deeper validation.
