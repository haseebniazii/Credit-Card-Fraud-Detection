<h1 align="center">💳 Credit Card Fraud Detection 💳</h1>

<p align="center">
  🚀 Machine Learning Project | 📊 Classification | 📈 Logistic Regression
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikit-learn">
  <img src="https://img.shields.io/badge/Model-Logistic%20Regression-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Problem-Classification-purple?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
</p>

---

## 📌 About The Project

**Credit Card Fraud Detection** is a Machine Learning classification project designed to identify fraudulent credit card transactions.

The project uses **Logistic Regression** to classify transactions as either legitimate or fraudulent.

The workflow includes data preprocessing, exploratory data analysis, feature scaling, model training, and model evaluation.

---

## 🎯 Objective

The main objective of this project is to build a Machine Learning model that can detect fraudulent credit card transactions and distinguish them from legitimate transactions.

---

## 📊 Dataset

The dataset contains credit card transaction records with anonymized numerical features.

The target variable is:

- `0` → Legitimate Transaction
- `1` → Fraudulent Transaction

### Features

The dataset includes:

- Time
- V1
- V2
- V3
- V4
- ...
- V28
- Amount

---

## 🤖 Machine Learning Model

### 📈 Logistic Regression

The project uses **Logistic Regression**, a classification algorithm suitable for binary classification problems.

```python
from sklearn.linear_model import LogisticRegression

model = LogisticRegression()

model.fit(X_train, y_train)
