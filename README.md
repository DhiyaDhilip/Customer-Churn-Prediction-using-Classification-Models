# Customer-Churn-Prediction-using-Classification-Models
Developed a machine-learning model to predict customer churn using classification algorithms. Performed EDA, feature engineering, scaling, and model comparison. Achieved high accuracy and deployed a Streamlit app for real-time customer churn prediction.

# 📦 Customer Churn Prediction using Machine Learning

This project predicts whether a customer will churn using classification algorithms. It covers complete EDA, preprocessing, model building, performance comparison, and deployment using Streamlit.

---

## 🚀 Project Overview
The objective is to classify customers as **Churn** or **Not Churn** based on demographics, usage behavior, and account information. Multiple ML models were trained and evaluated to choose the best performer.

---

## 📊 Dataset
Dataset Used: **Telco Customer Churn**  
Target Variable: `Churn` (Yes/No)  

Features include:
- Demographics
- Contract type
- Tenure
- Payment method
- Monthly & total charges

---

## 🔍 Exploratory Data Analysis (EDA)
Performed:
- Missing value handling  
- Outlier detection  
- Target distribution  
- Churn ratio study  
- Correlation matrix  
- Feature importance visualizations  

Key Insights:
- Month-to-month contract customers show high churn.
- Higher monthly charges increase churn probability.

---

## 🧹 Data Preprocessing
- Label encoding & one-hot encoding  
- Scaling numerical features  
- Handling imbalances using SMOTE  
- Train–test split  

---

## 🤖 Models Used
1. Logistic Regression  
2. Random Forest Classifier  
3. XGBoost Classifier  

**Metrics:** Accuracy, Precision, Recall, F1-Score, ROC-AUC

XGBoost provided the best results.

---

## 🏆 Model Saving
Saved:
- `best_model.pkl`
- `model_columns.pkl`
- `scaler.pkl`

Used for deployment in the Streamlit app.

---

## 🖥️ Streamlit Web App
A simple UI where users enter customer details and get the churn probability.

Run:
```bash
streamlit run app.py
