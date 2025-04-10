# 🧠 CRM Deal Closure Time Prediction

This project is a machine learning-driven analysis of how long it takes for deals to close in a CRM system. Using real business data extracted from a PostgreSQL database, the goal is to understand deal behavior and predict future closure times based on historical patterns.

## 📊 Project Overview

- **Goal:** Predict the time it takes for a deal to close based on CRM data.
- **Tech Stack:** Python, Pandas, NumPy, SQLAlchemy, PostgreSQL, scikit-learn.
- **Machine Learning Model:** Decision Tree Regressor.

## 🔍 Features

- Connects to a PostgreSQL database using SQLAlchemy.
- Extracts and preprocesses CRM data related to deal lifecycle.
- Performs exploratory data analysis (EDA).
- Trains and evaluates a regression model.
- Prepares the foundation for future model improvements and deployment.

## 📁 Project Structure

├── eda_adsim.ipynb # Main notebook with EDA and model 

├── adsim_config.py # Configuration for DB access and tokens (not included) 

├── requirements.txt # Dependencies

## 🛠️ Requirements

- Python 3.8+
- Pandas, NumPy, scikit-learn, SQLAlchemy, psycopg2
- Access to the CRM PostgreSQL database

## 🚀 Future Improvements

- Model evaluation and hyperparameter tuning
- Experimenting with other regression models (Random Forest, XGBoost)
- Deploying as an API or dashboard
- Improving feature engineering

## ✍️ Author

Developed by Guilherme Rodrigues, a data science student exploring real-world ML applications.
