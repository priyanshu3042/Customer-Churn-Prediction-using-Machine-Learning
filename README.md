# 📊 Customer Churn Prediction using Machine Learning

This project predicts whether a customer will churn (leave) a telecom service provider using machine learning models. It is built on the Telco Customer Churn dataset and provides actionable insights to help businesses reduce churn and improve customer retention.

---

## 🔍 Problem Statement

Customer churn is a critical issue for subscription-based companies. By identifying customers at high risk of leaving, companies can take proactive steps such as offering incentives or personalized services.

---

## 🧠 Techniques Used

- Data Cleaning & Imputation
- Exploratory Data Analysis (EDA)
- Label Encoding & One-Hot Encoding
- Feature Scaling with StandardScaler
- Model Training (Random Forest Classifier)
- Model Evaluation (Accuracy, Classification Report, Confusion Matrix)
- Feature Importance Visualization

---

## 📂 Dataset

- **Source**: [Telco Customer Churn - Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Contains customer information such as services signed up for, account info, and whether they churned.

---

## 📈 Model Performance

- **Model**: Random Forest Classifier
- **Accuracy**: ~80-85% (varies with random state)
- Shows which features (like Contract Type, Monthly Charges) most influence churn.

---

## 📌 Requirements

Install the following libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
