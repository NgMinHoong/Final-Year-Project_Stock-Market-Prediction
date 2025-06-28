# Deep Learning Models

This folder includes LSTM, GRU, and hybrid model notebooks for stock price prediction of

- Amazon (AMZN)
- Google (GOOG)
- Microsoft (MSFT)

## Models

- **LSTM**
- **GRU**
- **LSTM-GRU**: LSTM → GRU
- **GRU-LSTM**: GRU → LSTM

## Structure

Each model:
- Uses a 30-time-step sequence window
- Applies MinMaxScaler for normalization
- Evaluated using RMSE and R²
- Tuned using Random Search

## Files

- `AMZN_DL Stock Price Prediction.ipynb`
- `GOOG_DL Stock Price Prediction.ipynb`
- `MSFT_DL Stock Price Prediction.ipynb`
