Customer-Churn-Prediction
Machine Learning project to predict customer churn using Logistic Regression
This project focuses on predicting customer churn for a telecommunications company using machine learning techniques. Customer churn refers to customers who stop using a company's services, and predicting this behavior helps businesses take proactive actions to retain customers.

The dataset contains customer demographic details, account information, and service usage patterns. The project begins with data cleaning, including handling missing values and converting data types (such as transforming the TotalCharges column into numeric format).

Exploratory Data Analysis (EDA) was performed using visualizations to understand patterns and relationships between features and churn. Key observations include:

Customers with month-to-month contracts have a higher churn rate
Higher monthly charges are associated with increased churn
Customers with longer tenure are less likely to churn

Categorical variables were converted into numerical format using one-hot encoding to make them suitable for machine learning algorithms.

A Logistic Regression model was trained on the processed dataset. Before training, the data was split into training and testing sets. The model achieved an accuracy of approximately 81.30%, indicating good performance for a baseline model.

This project demonstrates the complete machine learning workflow:

Data preprocessing
Visualization and analysis
Feature engineering
Model building
Performance evaluation
