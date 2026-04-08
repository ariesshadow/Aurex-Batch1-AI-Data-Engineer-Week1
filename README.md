Customer Churn Prediction: Aurex AI/Data Engineering (Batch 1)

📌 Project Overview: 
This repository contains the Week 1 Project for the Aurex AI & Data Engineering program. The goal is to perform a comprehensive analysis of the Telco Customer Churn dataset to identify key drivers of customer attrition and build a baseline machine learning model for prediction.

📂 Project Structure: 
Customer_Churn_Analysis.ipynb: A structured Jupyter Notebook containing data ingestion, cleaning, EDA, and modeling.
WA_Fn-UseC_-Telco-Customer-Churn.csv: The primary dataset used for the analysis.

🛠️ Implementation PhasesAs per the program schedule, the project follows a 7-day structured workflow:
Environment Setup & Ingestion: Loading data and initial inspection.
Preprocessing: Handling missing values in TotalCharges (imputed with median) and encoding categorical features.
Pipeline Construction: Train-test splitting (80/20) and feature scaling using StandardScaler.
Exploratory Data Analysis (EDA): Visualizing distributions, correlations, and churn patterns.
Modeling & Evaluation: Comparison between Logistic Regression and Decision Tree models.

📊 Key FindingsChurn Drivers: High monthly charges and month-to-month contracts are the strongest indicators of churn.
Customer Tenure: New customers are significantly more likely to churn compared to those with long-term tenures.
Metric Focus: In this analysis, Recall was prioritized over Accuracy to ensure the business captures as many potential churners as possible.

Recommendation: The Decision Tree model is recommended for its higher Recall, which is more valuable for proactive customer retention strategies.
