# 📈 Stock Market Prediction System

A Django-based machine learning application for analyzing historical stock-market data and generating short-term stock-price predictions using statistical and machine-learning techniques.

## 🚀 Overview

The Stock Market Prediction System is an academic machine-learning project built with Python and Django.

The application retrieves historical stock-market data, performs data preprocessing and feature engineering, and applies predictive models to estimate future stock prices.

The system is designed as an educational project for exploring:

- Stock-market data analysis
- Feature engineering
- Time-series forecasting
- Machine learning
- Data visualization
- Web application development with Django

> ⚠️ This project is intended for educational and research purposes. Stock-market predictions are uncertain and should not be treated as financial advice.

---

## ✨ Features

### 📊 Historical Stock Data

The application can retrieve stock-market data for analysis and prediction.

The project uses `yfinance` for financial data retrieval.

### 🤖 Prediction Models

The prediction engine currently includes:

- Linear Regression
- ARIMA time-series forecasting
- LSTM-style prediction demonstration

> Note: The current LSTM implementation is a mock/demo implementation rather than a trained TensorFlow/Keras neural network.

### 📐 Feature Engineering

The prediction system processes historical market data and derives features such as:

- Open price
- High price
- Low price
- Closing price
- Trading volume
- 5-day moving average
- 20-day moving average
- Daily returns
- Rolling volatility
- Day-of-week features

### 📈 Data Visualization

The project includes data visualization capabilities using Python visualization libraries.

### 🌐 Django Web Application

The system provides a web interface built using:

- Django
- HTML
- CSS
- JavaScript
- Django templates

### 🗄️ Database

The project uses SQLite for local database storage through Django.

---

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Web Framework | Django |
| Machine Learning | Scikit-learn |
| Time-Series Analysis | Statsmodels |
| Data Processing | NumPy, Pandas |
| Financial Data | yfinance |
| Visualization | Matplotlib, Plotly |
| Database | SQLite |
| Frontend | HTML, CSS, JavaScript |
| Development Tools | Git, GitHub |

---

## 📁 Project Structure

```text
Stock-marketprediction-system/
│
├── predictor/
│   ├── migrations/
│   ├── templates/
│   │   └── predictor/
│   ├── admin.py
│   ├── apps.py
│   ├── data_fetcher.py
│   ├── forms.py
│   ├── ml_models.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── stock_prediction/
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── static/
│
├── staticfiles/
│
├── sample/
│
├── manage.py
├── requirements.txt
├── db.sqlite3
├── .gitattributes
├── README.md
└── readme.txt
