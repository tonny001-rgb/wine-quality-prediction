# 🍷 Wine Quality Prediction Using Machine Learning

## 📌 Project Overview
This project focuses on predicting the quality of wine using machine learning techniques. The dataset contains physicochemical properties of wine, and the goal is to build a model that can accurately predict wine quality scores.

We explore the data, perform preprocessing, build regression models, and evaluate their performance.



## 🎯 Objectives
- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess the dataset
- Handle missing values and categorical features
- Scale numerical features
- Build machine learning models
- Compare model performance
- Select the best performing model

---

## 📊 Dataset Description
The dataset includes physicochemical properties such as:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Wine type (red/white)
- Quality (target variable)

---

## 🧹 Data Preprocessing
- Handled missing values using median imputation
- Encoded categorical variables (wine type)
- Scaled features using StandardScaler
- Split dataset into training and testing sets

---

## 🤖 Models Used
- Linear Regression (baseline model)
- Ridge Regression (regularized model)

---

## 📈 Model Evaluation Metrics
- Mean Squared Error (MSE)
- R² Score

---

## 🏆 Results
The models were compared based on their performance on unseen test data. Ridge Regression helped reduce overfitting and provided more stable predictions.

---

## 📦 Files in This Repository
- `notebook.ipynb` → Main analysis and modeling notebook
- `wine_model.pkl` → Saved trained machine learning model
- `README.md` → Project documentation

---

## 🚀 How to Run This Project
1. Clone the repository:
```bash
git clone https://github.com/tonny001-rgb/wine-quality-prediction.git
