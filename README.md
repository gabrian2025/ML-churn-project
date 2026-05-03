# Customer Churn Prediction (Machine Learning Project)

This project builds a machine learning model to predict whether a customer will churn (leave a service) based on demographic, account, and service usage data.

The goal is to demonstrate an end-to-end machine learning pipeline including data preprocessing, feature engineering, model training, and evaluation.

---

# Project Overview

Customer churn is a critical problem in subscription-based businesses. In this project, we use supervised machine learning to classify whether a customer is likely to churn.

We compare multiple models and evaluate performance using standard classification metrics.

---

# Dataset

The dataset contains customer information such as:

- Demographics (gender, senior citizen, partner, dependents)
- Account information (tenure, contract type, payment method)
- Services used (internet service, online security, tech support, etc.)
- Billing information (monthly charges, total charges)
- Target variable: `Churn`

---

# Technologies Used

- Python
- pandas
- NumPy
- scikit-learn
- matplotlib
- seaborn
- Jupyter Notebook

---

# Data Preprocessing (ETL Pipeline)

- Removed irrelevant column: `customerID`
- Handled missing values in `TotalCharges`
- Converted categorical variables using one-hot encoding (`pd.get_dummies`)
- Converted data types for model compatibility

---

# Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- Random Forest Classifier

---

## 📊 Model Evaluation

Performance was measured using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

### Best Result:
- Accuracy: ~79%
- Logistic Regreesion performed better in identifying churn customers



---

## 📂 Project Structure
