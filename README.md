# FUTURE_ML_03
  Customer Churn Prediction (E-commerce)
CIN: FIT/FEB26/ML5800

   Project Overview
This project (Task 3) focuses on Predictive Analytics to identify customers at risk of leaving an e-commerce platform. By merging customer behavior data with historical churn results, I developed a model to forecast future retention.

   Data Insights
Churn Rate Analysis : I first calculated the distribution of active vs. churned customers to understand the dataset balance.
Pie Chart Visualization : Visualized the retention rate to identify the scale of the business problem.

 Technical Workflow
Data Merging : Combined ecommerce_customer_features.csvand ecommerce_customer_targets.csvon the Customer_IDcolumn.
Feature Engineering : Converted categorical variables (like Loyalty Member status) into numerical format for the model.
Modeling : Utilized a Random Forest Classifier to handle complex numerical patterns in customer behavior.
Evaluation : Generated a Confusion Matrix to measure the Precision and Recall of churn predictions.

 Repository Files
FUTURE_ML_03.ipynb: Full Python implementation, EDA, and model evaluation.
ecommerce_customer_features.csv: Customer behavior data .
ecommerce_customer_targets.csv: Actual churn labels (Yes/No).
