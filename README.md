# 💳 Fraud Detection ML App

This repository contains a complete **Fraud Detection Project** that covers:
- Exploratory Data Analysis (EDA)
- Preprocessing of imbalanced datasets
- Training and evaluation of Machine Learning models
- Deployment of a simple **Streamlit web application** for fraud prediction

---

## 📌 Project Overview
Credit card fraud is a critical challenge in financial systems worldwide.  
Using a highly imbalanced dataset of real-world transactions, we tested different models to identify fraudulent activities.

### Objectives
- Perform **EDA** to understand patterns and imbalance.
- Apply **scaling, normalization, and resampling techniques**.
- Build and compare ML models:
  - Logistic Regression
  - Random Forest
  - XGBoost
- Evaluate performance using **ROC-AUC, Precision, Recall, and F1-score**.
- Deploy a lightweight **Streamlit app** for real-time fraud prediction.

---

## 📊 Key Results
- Logistic Regression: High recall but many false positives.
- Random Forest: Best balance, with ~99.97% accuracy and strong F1-score.
- XGBoost: Extremely high recall (0.99), ideal for catching nearly all fraud cases, though with lower precision.

👉 **Random Forest proved to be the most practical model for production**, minimizing false alarms while still detecting fraud effectively.

---

## 🚀 Streamlit Application
A simple web app was built to interact with the trained model.

Run locally with:
```bash
streamlit run fraud_detection.py

## 📊 Key Visualizations

<p align="center">
  <img src="Amount%20vs%20isFraud%20(Filtered%20under%2050,000).png" width="600" alt="Amount vs isFraud">
</p>

<p align="center">
  <img src="Correlation Matrix.png" width="600" alt="Correlation Matrix">
</p>

<p align="center">
  <img src="Fraud%20Distribution%20in%20Transfer%20and%20Cash%20Out%20Ty....png" width="600" alt="Fraud Distribution in Transfer and Cash Out">
</p>

<p align="center">
  <img src="Fraud%20Rate%20By%20Transaction%20plot.png" width="600" alt="Fraud Rate by Transaction">
</p>

<p align="center">
  <img src="Log-Transformed%20Transaction%20Amount%20Distribut....png" width="600" alt="Log-Transformed Transaction Amount Distribution">
</p>

<p align="center">
  <img src="transaction%20type%20distribution.png" width="600" alt="Transaction Type Distribution">
</p>



