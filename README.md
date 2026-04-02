<div align="center">

# 📊 Credit Default Prediction using Machine Learning

*Predicting whether a customer is likely to default on credit using machine learning algorithms to aid in financial risk assessment and decision-making.*

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

</div>

---

## 📌 Project Overview
Credit default prediction is a critical task in the financial domain. Incorrect predictions can lead to:
* 💸 **Financial losses**
* ⚠️ **Poor lending decisions**

This project assesses financial risk by classifying customers into two distinct categories:
* ✅ **Non-Default:** Good Credit Risk
* ❌ **Default:** Bad Credit Risk

---

## 🗂️ Dataset Information
* 🔗 **Dataset Link:** [UCI Statlog (German Credit Data)](http://archive.ics.uci.edu/dataset/144/statlog+german+credit+data)
* 🎯 **Target Variable:** `0` → No Default | `1` → Default

**📊 Dataset Features Analyzed:**
* 👤 Customer demographic details
* 💰 Financial information
* 📊 Credit history
* ⏳ Loan duration and amount

---

## ⚙️ Technologies & Workflow

**Tech Stack:**
* 🐍 Python
* 📦 Pandas & NumPy
* 📊 Matplotlib
* 🤖 Scikit-learn

**🔄 Machine Learning Workflow:**
`Data` ➔ `Preprocessing` ➔ `Train/Test Split` ➔ `Model Training` ➔ `Evaluation`

---

## 🧠 Machine Learning Models & Key Insights

Our team implemented and evaluated four distinct supervised learning algorithms. They were evaluated using **Accuracy, Precision, Recall, F1-Score, and ROC-AUC**.

| Algorithm | Key Insight |
| :--- | :--- |
| 🌳 **Decision Tree** | Achieved high recall, making it very good at detecting actual defaulters. |
| 📍 **K-Nearest Neighbors (KNN)** | Delivered moderate overall performance. |
| 📈 **Logistic Regression** | Provided the best overall balance between metrics. |
| ⚡ **Gradient Boosting** | Yielded the highest overall predictive accuracy. |

---

## 🧪 Results Summary

| Model Rank | Algorithm | Accuracy Score |
| :---: | :--- | :---: |
| 🥇 | **⚡ Gradient Boosting** | `0.73` |
| 🥈 | **📈 Logistic Regression** | `0.72` |
| 🥉 | **📍 K-Nearest Neighbors (KNN)** | `0.68` |
| 🏅 | **🌳 Decision Tree** | `0.62` |

---

## 📂 Project Structure
```bash
📁 Credit-Default-Prediction
│
├── decision_tree.ipynb         # Implementation of the Decision Tree model
├── logistic_regression.ipynb   # Implementation of the Logistic Regression model
├── german_credit_knn.ipynb     # Implementation of the KNN model
└── gradient_boosting.ipynb     # Implementation of the Gradient Boosting model
