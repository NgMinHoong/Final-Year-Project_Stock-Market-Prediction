# ARIMA Models

This folder contains Jupyter notebooks implementing ARIMA stock price prediction models for:

- Amazon (AMZN)
- Google (GOOG)
- Microsoft (MSFT)

## Workflow

1. Data loaded using `yfinance`
2. Stationarity tested using ADF
3. ARIMA parameters selected via ACF/PACF plots
4. Hyperparameter Tuning
5. Model evaluated using RMSE and R²

## Files

- `AMZN_ARIMA Stock Price Prediction.ipynb`
- `GOOG_ARIMA Stock Price Prediction.ipynb`
- `MSFT_ARIMA Stock Price Prediction.ipynb`
