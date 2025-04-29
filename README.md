Time Series Forecasting - Model Comparison

This repository contains implementations of four different time series forecasting models applied to the Air Passengers dataset.
The goal is to evaluate and compare the predictive performance of the following classical forecasting techniques:

SES (Simple Exponential Smoothing) :- Forecasts based on weighted averages of past observations, with more weight given to recent observations.

DES (Double Exponential Smoothing) :- Accounts for trends in the data using two smoothing equations.

TES (Triple Exponential Smoothing/Holt-Winters) :- Incorporates seasonality in addition to trend and level. Suitable for seasonal time series.

ARIMA (AutoRegressive Integrated Moving Average) :- Combines autoregressive and moving average components, including differencing to ensure stationarity.

📊 Dataset

All models are trained on the Air Passengers dataset, which records monthly totals of international airline passengers

📈 Outputs

Each notebook:

Loads and visualizes the time series data.

Applies the respective model.

Generates forecasts and compares them with actual values.

Visualizes the results for interpretability
