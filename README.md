⛽ Petrol Price Prediction
📝 Project Overview

This project focuses on predicting petrol (gasoline) prices using historical fuel data and related economic indicators. The aim is to analyze price fluctuations, identify influencing factors, and build predictive models to assist in budgeting, policy-making, and consumer forecasting.

🎯 Objectives

Perform EDA on petrol price datasets across time.

Study the relationship between petrol prices and macroeconomic variables (crude oil, inflation, currency exchange rates).

Build regression and time series models to forecast petrol prices.

Evaluate model accuracy with error metrics and visualize trends.

🗂️ Dataset

Source: Government fuel price dataset / Kaggle / Petroleum ministry reports.

Columns:

Date

Petrol Price (₹/liter or $/gallon)

Crude Oil Price (Brent / WTI)

USD/INR exchange rate

Inflation index (CPI)

Diesel price (optional comparison)

Rows: ~5,000+ daily/weekly records.

File format: .csv

🔧 Tools & Technologies

Python → Pandas, NumPy

Visualization → Matplotlib, Seaborn

Machine Learning → Scikit-learn (Linear Regression, Random Forest, XGBoost)

Time Series → ARIMA, SARIMA, Prophet

Jupyter Notebook for analysis

📈 Methodology

Data Cleaning & Preprocessing

Handle missing price records

Convert date column to datetime

Normalize variables

Exploratory Data Analysis (EDA)

Plot petrol price trends over years

Correlation heatmap (petrol vs crude oil, exchange rate, inflation)

Rolling averages for seasonal trends

Feature Engineering

Lag features (previous day/week/month prices)

Moving average & volatility

Derived ratios (petrol-to-crude price ratio)

Model Building

Linear Regression → baseline prediction

Random Forest & XGBoost → machine learning regression

ARIMA / Prophet → time series forecasting

Evaluation Metrics

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

📊 Key Insights

Petrol prices are strongly correlated with crude oil and exchange rates (USD/INR).

Inflation impact is moderate but consistent.

Machine learning models like XGBoost performed better than simple linear regression.

Seasonal variation patterns visible around international oil market shocks.

📌 Outcomes

Built a petrol price prediction model with R² ≈ 0.82.

Forecasts provide short-term reliability (1–2 months) but long-term trends remain volatile.

Dashboards show real-time petrol price vs crude oil relationship.

🚀 Future Work

Deploy a Streamlit dashboard for live predictions.

Integrate real-time APIs for crude oil prices and currency exchange rates.

Experiment with LSTM (Deep Learning) for improved time series forecasting.
