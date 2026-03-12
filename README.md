Classification - Flipkart Customer Service Satisfaction
Project Overview
This project aims to build a machine learning classification model to predict Customer Satisfaction Scores (CSAT) (ranging from 1 to 5) based on historical customer support interaction data. By analyzing various factors like past interactions, agent behavior, customer remarks, and ticket resolution times, the model proactively identifies areas needing improvement and optimizes support workflows for Flipkart.

Problem Statement
In a competitive environment, exceptional customer support is vital for retention. Relying on post-interaction CSAT feedback is often reactive. This project develops a machine learning classification model to predict CSAT scores proactively from historical support data. By analyzing structured data such as ticket handling time, agent performance, issue type, and metadata, the goal is to enable early intervention to improve service experience and customer loyalty.

Dataset
The project utilizes the Customer_support_data.csv dataset, which contains multiple entries from a customer support system. Each row represents a unique customer interaction with metadata such as:

channel_name: Communication channel used by the customer (e.g., Email, Chat, Phone).
category: Broad classification of the support issue (e.g., Technical, Billing, Account).
Sub-category: More specific issue label (e.g., "Login Failure").
Customer Remarks: Free-text input from customers.
Issue_reported at & issue_responded: Timestamps for calculating response and resolution delays.
Customer_City, Product_category, Item_price.
connected_handling_time: Total time spent by the agent.
Agent_name, Supervisor, Manager, Tenure Bucket, Agent Shift.
CSAT Score: The target variable (1 to 5).
Use Cases
This classification model can be used by customer service teams to:

Flag at-risk tickets likely to receive low CSAT scores.
Identify factors leading to dissatisfaction.
Guide training and resource allocation to improve service quality.
Technologies Used
Python
Jupyter Notebook
Pandas: For data manipulation.
NumPy: For numerical operations.
Matplotlib & Seaborn: For data visualization.
Scikit-learn: For model selection (train_test_split, GridSearchCV, cross_val_score), preprocessing (LabelEncoder, StandardScaler), and evaluation metrics (classification_report, accuracy_score, precision_score, recall_score, f1_score).
RandomForestClassifier
XGBoost (XGBClassifier)
