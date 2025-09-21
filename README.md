# Customer-Churn_Prediction

requirements and dependencies

streamlit==1.34.0
pandas==2.2.2
numpy==1.26.4
scikit-learn==1.4.2
matplotlib==3.8.4
seaborn==0.13.2
imbalanced-learn==0.11.0
joblib==1.4.0

📊 Customer Churn Prediction Web App

This project predicts whether a customer is likely to churn (leave the service) based on their demographics and account information. It uses a Machine Learning model (Logistic Regression) trained on the Telco Customer Churn Dataset and provides an interactive Streamlit web app for predictions.

🚀 Tech Stack

-Python – Core programming language
-Pandas – Data preprocessing and manipulation
-Scikit-learn – Model training (Logistic Regression)
-Joblib – Saving/loading the trained ML model

⚡ Features

-User-friendly web interface for churn prediction
-Dropdowns, sliders, and number inputs for customer data entry
-Displays results clearly (Likely to churn ✅ / Not likely to churn ❌)
-Reusable ML pipeline with saved model (.pkl)

📊 Dataset

The project uses the Telco Customer Churn dataset, which includes:
-Demographics (gender, senior citizen, partner, dependents)
-Customer account info (tenure, monthly charges, total charges)
-Target variable: Churn (Yes/No)

Dataset source: #!/bin/bash
curl -L -o ~/Downloads/telco-customer-churn.zip\
  https://www.kaggle.com/api/v1/datasets/download/blastchar/telco-customer-churn
  
🌐 Deployment

You can deploy this app online using:
-Streamlit Community Cloud
Streamlit – Building the web interface

Google Colab – Model development environment
