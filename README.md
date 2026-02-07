# "Online Payment Fraud Detection using Machine Learning"


# PROJECT OVERVIEW

With the rapid growth of digital payments, fraudulent transactions have become a major concern.  
This project builds a Machine Learning system to detect fraudulent online payment transactions.
The model predicts whether a transaction is:
- 0 → Non-Fraud  
- 1 → Fraud  
The goal is to help financial systems identify suspicious transactions and reduce fraud risk.

# FEATURES

- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature encoding and scaling  
- Multiple ML model comparison  
- Fraud prediction system  
- Model evaluation using ROC-AUC and confusion matrix

# TECH STACK

- Python  
- Google Colab  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- XGBoost
  The dataset contains real-world styled online transaction records with features like:

| Feature | Description |
|--------|------------|
| step | Unit of time |
| type | Transaction type |
| amount | Transaction amount |
| oldbalanceOrg | Sender balance before |
| newbalanceOrg | Sender balance after |
| oldbalanceDest | Receiver balance before |
| newbalanceDest | Receiver balance after |
| isFraud | Target variable (0/1) |
Note: 
The dataset is large and cannot be uploaded to GitHub.
# Exploratory Data Analysis

- Transaction type distribution plotted  
- Fraud vs Non-fraud count analysis  
- Step distribution visualization  
- Correlation heatmap between features
#  Machine Learning Models Used

- Logistic Regression  
- XGBoost Classifier  
  - Random Forest Classifier  

Models were compared using ROC-AUC score
# results

- Successfully detected fraudulent transactions  
- Compared multiple ML models  
- Achieved high ROC-AUC score of 0.986
- Identified XGBoost as best performing model  





