# 📉 Customer Churn Prediction (Machine Learning Project)

## 📌 Project Overview
This project predicts whether a customer will churn (leave the service) using machine learning classification models.

## 📊 Dataset
- Source: Kaggle (Telco Customer Churn Dataset)
- Target Variable: Churn (Yes / No)

## 🔍 Steps Performed
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Encoding categorical variables
- Model Training (Logistic Regression)
- Handling class imbalance
- Model Evaluation

## ⚙️ Features Used
- tenure
- MonthlyCharges
- TotalCharges
- Contract
- InternetService
- PaymentMethod
- and more...

## 🤖 Model Used
- Logistic Regression

## 📈 Results

### Before Handling Imbalance:
- Accuracy: 0.82
- Recall (Churn = Yes): 0.58

### After Handling Imbalance:
- Accuracy: 0.76
- Recall (Churn = Yes): 0.83

## 💡 Key Insights
- Customers with month-to-month contracts have higher churn
- Customers with low tenure are more likely to leave
- High monthly charges correlate with higher churn
- Fiber optic users showed higher churn rates

## 🚀 Business Insight
Improving recall allows the company to identify most customers at risk of leaving and take preventive actions (discounts, retention campaigns).

## 🔧 Future Improvements
- Try Random Forest / XGBoost
- Hyperparameter tuning
- Feature selection

## 👨‍💻 Author
Hossein Fathi
