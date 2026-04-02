📊 Credit Default Prediction using Machine Learning

🚀 This project focuses on predicting whether a customer is likely to default on credit using machine learning algorithms. It helps in financial risk assessment and decision-making.

📌 Project Overview

Credit default prediction is a critical task in the financial domain. Incorrect predictions can lead to:

💸 Financial losses
⚠️ Poor lending decisions

This project classifies customers into:

✅ Non-Default (Good Credit Risk)
❌ Default (Bad Credit Risk)
🗂️ Dataset

📁 German Credit Dataset

🔗 Dataset Link:
👉 UCI German Credit Dataset

📊 Dataset Features:
👤 Customer demographic details
💰 Financial information
📊 Credit history
⏳ Loan duration and amount
🎯 Target Variable:
0 → No Default
1 → Default
⚙️ Technologies Used
🐍 Python
📦 Pandas, NumPy
📊 Matplotlib
🤖 Scikit-learn
🧠 Machine Learning Models
🌳 Decision Tree
📍 K-Nearest Neighbors (KNN)
📈 Logistic Regression
⚡ Gradient Boosting
🔄 Workflow
Data → Preprocessing → Train/Test Split → Model Training → Evaluation
📊 Evaluation Metrics
🎯 Accuracy
🔍 Precision
📢 Recall
⚖️ F1-Score
📉 ROC-AUC
📌 Key Insights
🌳 Decision Tree → High recall (good at detecting defaulters)
📍 KNN → Moderate performance
📈 Logistic Regression → Best overall balance
⚡ Gradient Boosting → Highest accuracy
🧪 Results Summary

Model	Accuracy
⚡ Gradient Boosting	0.73
📈 Logistic Regression	0.72
📍 KNN	0.68
🌳 Decision Tree	0.62

📂 Project Structure
📁 Credit-Default-Prediction
│
├── decision_tree.ipynb
├── logistic_regression.ipynb
├── german_credit_knn.ipynb
├── gradient_boosting.ipynb
