# Gold Price Prediction for the Next 30 Days

This project predicts the price of gold for the next 30 days using a machine learning model, specifically a **Random Forest Regressor**. The model is trained on historical gold price data from 2001 to the current date (2024-10-11). The features used include lagged returns, moving averages, and volatility.

## Table of Contents

- [Requirements](#requirements)
- [Data](#data)
## Requirements

To run this project on Google Colab, you need the following Python libraries:

- `yfinance`
- `pandas`
- `numpy`
- `sklearn`
- `matplotlib`
## Data
We use gold price data from Yahoo Finance, specifically the gold futures ticker GC=F. Data is collected from January 1, 2001, to the current date (October 11, 2024).

- Source: Yahoo Finance Gold Futures
- The dataset includes the following columns:
- Adj Close: The adjusted closing price of gold.
- Return: Daily percentage return of the adjusted close price.
- SMA_10: 10-day simple moving average.
- SMA_30: 30-day simple moving average.
- Volatility: 10-day rolling standard deviation of the adjusted close price.
