
---

# 📊 Telecom Customer Churn Prediction

## 📌 Problem Statement

A telecom company is facing high customer churn.
The objective is to build a **machine learning model** that predicts whether a customer will **churn (Yes/No)** so the business can take preventive actions.

---

## 📂 Dataset

Each row represents a customer with the following features:

* CustomerID (identifier)
* Gender, Age
* MonthlyCharges
* Tenure (months with company)
* ContractType (Monthly / Annual / 2-Year)
* InternetService
* SupportTickets (complaints)
* PaymentMethod
* **Churn (Target Variable)**

---

## 🎯 Objective

Build a classification model to predict:

```
Churn = Yes or No
```

---

## ⚙️ Logic & Implementation

### 1️⃣ Data Understanding

* Identified **input features** and **target variable**
* Checked for **missing values and outliers**
* Performed basic **EDA** to understand churn patterns

---

### 2️⃣ Data Preprocessing

* Categorical features encoded using **One-Hot Encoding**
* Numerical features scaled using **StandardScaler**
* Dataset split into **train and test sets**

---

### 3️⃣ Model Building

Trained and compared:

* **Logistic Regression**
* **Random Forest Classifier**

Random Forest was selected due to **better performance and feature importance interpretability**.

---

### 4️⃣ Model Evaluation

Evaluated using:

* Accuracy
* Precision, Recall, F1-score
* Confusion Matrix
* ROC-AUC Score



---

## 📈 Key Insights

* Customers with **short tenure**, **high monthly charges**, and **many support tickets** are more likely to churn.
* Customers with **Annual or 2-Year contracts** show **lower churn probability**.

---

## 🧰 Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Google Colab

---

