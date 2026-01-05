# Crypto_Market_Intelligence-Using-Multi-Regression-Models-With-Streamlit-Dashboard

# ₿ BTC Close Price Prediction Web App

This project is a **Streamlit-based web application** that predicts the **Bitcoin (BTC) closing price** using a **Random Forest Regression model**.  
The prediction is based on the closing prices and trading volumes of **USDT** and **BNB**.

---

## 🚀 Project Overview

Cryptocurrency prices are influenced by multiple market factors.  
This application leverages machine learning to estimate BTC closing prices using correlated crypto market data.

The trained **Random Forest Regressor** is loaded from a serialized `.pkl` file and deployed through an interactive Streamlit interface.

---

## 🧠 Machine Learning Model

- **Algorithm:** Random Forest Regressor  
- **Target Variable:** BTC Close Price  
- **Input Features:**
  - USDT Close Price
  - USDT Volume
  - BNB Close Price
  - BNB Volume

---

## 🛠️ Technologies Used

- **Python**
- **Streamlit** – Web application framework
- **Pandas** – Data handling
- **Scikit-learn** – Machine learning model
- **Pickle** – Model serialization

---

---

## 🔄 Application Workflow

1. Load the trained Random Forest model  
2. Accept user inputs through the Streamlit sidebar  
3. Convert inputs into a Pandas DataFrame  
4. Predict BTC closing price using the ML model  
5. Display the predicted value on the web interface  

---
