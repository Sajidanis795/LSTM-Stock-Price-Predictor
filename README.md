# Stock-Price-Predictor
This repository contains a Python script that uses a Long Short Term Memory (LSTM) model to predict the closing price of Tesla (symbol: 'tsla') for the next 5 trading days.

# Features
Download five years of historical data for Tesla from Yahoo Finance.
Normalize the input data using MinMaxScaler.
Create a training set and prepare it for use with an LSTM model.
Build an LSTM model with two LSTM layers and two dense layers.
Train the LSTM model on the historical data.
Predict the closing prices based on the model.
Plot the actual and predicted closing prices for the last 90 days.
Predict the closing price for the next trading day.
Requirements

# To install and run this project you need:

Python 3
pandas
numpy
yfinance
keras
sklearn
matplotlib
