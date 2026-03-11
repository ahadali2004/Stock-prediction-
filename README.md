# 📈 Stock Price Prediction using Machine Learning

This project demonstrates how **Machine Learning** can be used to predict the **next day's stock closing price** using historical market data.

The dataset is fetched from **Yahoo Finance** using the `yfinance` API. Features such as **Open, High, Low, and Volume** are used to train a **Linear Regression model** to predict future closing prices.

---

## 📊 Project Overview

| Feature | Details |
|--------|--------|
| Project Type | Machine Learning / Data Science |
| Model Used | Linear Regression |
| Data Source | Yahoo Finance |
| Language | Python |
| Objective | Predict the next day's stock closing price |

---

## 🛠 Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Scikit-learn**
- **yfinance API**

---

## 🚀 Project Workflow

### 1. Data Collection
- Retrieved historical stock market data using the **yfinance API**
- Loaded and structured data using **Pandas**

### 2. Data Exploration
- Examined dataset using:
  - `.head()`
  - `.info()`
  - `.describe()`
- Analyzed trends and distributions

### 3. Feature Engineering
- Selected important features:
  - Open
  - High
  - Low
  - Volume
- Target variable:
  - Closing Price

### 4. Model Training
- Implemented **Linear Regression** using **Scikit-learn**
- Trained the model using historical stock data

### 5. Prediction & Visualization
- Predicted the next day's closing price
- Compared **Actual vs Predicted prices**
- Visualized results using **Matplotlib**

---

## 📊 Learning Outcomes

This project helped improve my understanding of:

- Time-series financial data
- Data preprocessing with **Pandas**
- Regression models in **Machine Learning**
- Data visualization using **Matplotlib**

---

## 🎥 Project Demo

A short video demonstration explains:
- Project workflow
- Model training
- Prediction results

- DEMO VIDEO:
- https://www.linkedin.com/posts/ahadali200_datascience-machinelearning-python-activity-7437165381993000961-bx7U?utm_source=share&utm_medium=member_desktop&rcm=ACoAAGQFMOUB5_cvTNwP3WIdO-qJcvxyrV-zIJ8

---

## 📌 Future Improvements

- Implement advanced models such as:
  - Random Forest
  - LSTM
- Improve prediction accuracy
- Add real-time prediction dashboard
