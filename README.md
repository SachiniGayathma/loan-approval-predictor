📊 Credit Default Prediction using Machine Learning

🚀 This project focuses on predicting whether a customer is likely to default on credit using multiple machine learning algorithms. The goal is to analyze customer financial data and build predictive models to support risk assessment and decision-making in financial institutions.

📌 Project Overview

Credit default prediction is a critical problem in the financial domain. Incorrect predictions can lead to financial losses or missed opportunities.

This project applies different supervised learning algorithms to the German Credit Dataset to classify customers into:

✅ Non-Default (Good Credit Risk)
❌ Default (Bad Credit Risk)
🗂️ Dataset

📁 German Credit Dataset

🔗 Dataset Link:
http://archive.ics.uci.edu/dataset/144/statlog+german+credit+data

The dataset contains:

👤 Customer demographic details
💰 Financial information
📊 Credit history
⏳ Loan duration and amount

🔎 The target variable:

0 → No Default
1 → Default
⚙️ Technologies Used
🐍 Python
📦 Pandas, NumPy
📊 Matplotlib
🤖 Scikit-learn
🧠 Machine Learning Models

The following algorithms were implemented:

🌳 Decision Tree
📍 K-Nearest Neighbors (KNN)
📈 Logistic Regression
⚡ Gradient Boosting
🔄 Workflow
📥 Data Loading
🧹 Data Preprocessing
Handling categorical variables (One-Hot Encoding)
Feature transformation
✂️ Train-Test Split
🤖 Model Training
📊 Model Evaluation
📊 Evaluation Metrics
🎯 Accuracy
🔍 Precision
📢 Recall
⚖️ F1-Score
📉 ROC-AUC
📌 Key Insights
🌳 Decision Tree → High recall (detects defaulters well)
📍 KNN → Moderate performance
📈 Logistic Regression → Best balance across metrics
⚡ Gradient Boosting → Highest accuracy
🧪 Results Summary

Model	Accuracy
Gradient Boosting	0.73
Logistic Regression	0.72
KNN	0.68
Decision Tree	0.62

📂 Project Structure
📁 Credit-Default-Prediction
│
├── 📄 decision_tree.ipynb
├── 📄 logistic_regression.ipynb
├── 📄 german_credit_knn.ipynb
├── 📄 gradient_boosting.ipynb


