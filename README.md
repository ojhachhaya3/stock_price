# stock_price
This project demonstrates how to forecast Apple Inc. (AAPL) stock prices using a deep learning model built with a Stacked LSTM architecture. The aim is to predict future stock trends by leveraging historical data from Yahoo Finance and advanced time-series modeling techniques.

## Overview
Domain: Financial Time Series Forecasting
Objective: Predict future closing prices for Apple stocks using past trends.
Tech Stack: Python, TensorFlow/Keras, Pandas, NumPy, Matplotlib, Plotly.
Model: Stacked Long Short-Term Memory (LSTM).

 ## Features
Read historical stock data from CSV (sourced from Kaggle).
Preprocessing steps include:
* Normalization using MinMaxScaler.
* Sequence generation for time-series modeling.
Builds a Stacked LSTM network with multiple hidden layers to capture temporal dependencies.
Predicts and visualizes real vs predicted stock prices.
Evaluates model using MSE.
