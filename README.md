HEAD

# Customer Churn Prediction

## 1. Project Overview
This project predicts whether a telecom customer is likely to leave
the company using machine learning techniques.

## 2. Business Problem
Customer churn affects company revenue and customer retention.
The objective is to identify customers who are likely to discontinue
their services so that businesses can take preventive action.

## 3. Dataset
Dataset: IBM Telco Customer Churn

The dataset contains customer information, services, contract details,
billing information and the target variable Churn.

## 4. Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 5. Project Workflow
1. Data collection
2. Data inspection
3. Data cleaning
4. Exploratory Data Analysis (EDA)
5. Feature engineering
6. Data preprocessing
7. Model training
8. Model evaluation
9. Feature importance
10. Customer churn prediction

## 6. Machine Learning Models
- Logistic Regression
- Random Forest Classifier

## 7. Model Performance

The project evaluated two machine learning algorithms using a test dataset.

| Metric | Logistic Regression | Random Forest |
|---|---:|---:|
| Accuracy | 74.16% | 76.44% |
| Precision | 50.79% | 54.01% |
| Recall | 77.96% | 74.19% |
| F1 Score | 61.51% | 62.51% |
| ROC-AUC | 0.8398 | 0.8394 |

### Model Comparison

Random Forest achieved the highest accuracy (76.44%), precision (54.01%) and F1-score (62.51%).

Logistic Regression achieved higher recall (77.96%) and a marginally higher ROC-AUC (0.8398).

Random Forest was selected as the initial overall model based on its accuracy, precision and F1-score. Logistic Regression remains a competitive alternative when identifying more potential churners is the priority.

### Business Interpretation

The models can help identify customers who may discontinue their telecom services. Businesses can use these predictions to prioritise customer retention campaigns.

## 8. Project Outputs
The outputs folder contains trained models, visualisations,
feature importance results and customer prediction results.

## 9. Business Impact
The model can help businesses identify customers at risk of leaving
and support targeted customer retention strategies.

## 10. Author
Nageshwaran S
# Customer-Churn-Prediction
Customer churn prediction using Python, Exploratory Data Analysis, Logistic Regression and Random Forest.
3896314176d76e3c9f83c01a3c17dcdf51fa0ebb
