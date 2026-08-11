# Time Series Forecasting

Time series forecasting of short-term rental listing views using Prophet, MSTL and external regressors

# About the Project
This project focuses on time series analysis and forecasting of daily views of short-term rental listings in Kaliningrad.
The aim of the project is to analyze historical data, identify trends and seasonal patterns, evaluate the influence of external factors, compare different forecasting approaches, and build a forecast for the next year

# Data
The dataset contains daily observations from 2019 to 2022. The target variable is the daily number of short-term rental listing views/ Several external factors were also considered, including:
- Daily Active Users (DAU)
- COVID-19 period
- introduction of a new search feature
- holidays

# Steps
The analysis included:
- data preprocessing
- missing value handling
- exploratory time series analysis
- trend and seasonality decomposition
- feature engineering
- forecasting

# Models
The following forecasting methods were used:
- Prophet
- MSTL
- Auto-ARIMAX

# Evaluation
The forecasting models were evaluated with MAPE and time-series cross-validation.
The models were compared based on their forecasting accuracy and the behavior of their long-term forecasts



