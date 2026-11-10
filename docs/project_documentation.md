
# CUSTOMER CHURN PREDICTION
## Technical Project Documentation

### 1. Project Objective
To develop a machine learning system that predicts whether a
telecommunication customer is likely to leave the company.

### 2. Business Understanding
Customer churn results in revenue loss and increased customer
acquisition costs. Predicting potential churn helps businesses
take preventive retention measures.

### 3. Dataset Description
Dataset: IBM Telco Customer Churn

Target variable: Churn
- Yes: Customer left the company
- No: Customer continued the service

The dataset includes customer demographics, subscribed services,
contract information and billing details.

### 4. Data Cleaning
- Removed the customerID column.
- Converted TotalCharges into numeric format.
- Handled missing TotalCharges values.
- Checked for duplicate records.

### 5. Exploratory Data Analysis
Analysed:
- Overall customer churn distribution.
- Churn by contract type.
- Churn by internet service.
- Churn by payment method.
- Customer tenure.
- Monthly charges.
- Numerical feature correlations.

### 6. Feature Engineering and Preprocessing
- Separated independent and target variables.
- Converted churn labels into binary values.
- Identified numerical and categorical features.
- Applied StandardScaler to numerical features.
- Applied OneHotEncoder to categorical features.
- Split data into training and testing sets.

### 7. Machine Learning Models
Model 1: Logistic Regression
Model 2: Random Forest Classifier

### 8. Model Evaluation
Evaluation metrics:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

Actual model results will be added after reviewing the
evaluation output from the notebook.

### 9. Feature Importance
Random Forest feature importance was used to identify
features that contributed to model predictions.

### 10. Customer Prediction
The trained model was tested using hypothetical customer
profiles to estimate their churn probability.

### 11. Business Applications
- Identify customers at risk of leaving.
- Support targeted retention campaigns.
- Help customer relationship management teams.
- Improve customer retention strategies.

### 12. Limitations
- Predictions are based on historical dataset patterns.
- Model probabilities are estimates, not guarantees.
- Further validation is required before real-world deployment.

### 13. Future Enhancements
- Hyperparameter tuning.
- Model explainability using SHAP.
- Probability calibration.
- Deployment using Streamlit or Flask.
- Integration with a live customer database.

### 14. Conclusion
This project demonstrates an end-to-end machine learning
workflow for customer churn prediction, from data cleaning
and exploratory analysis to model evaluation and prediction.
