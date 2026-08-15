# Market Liquidity Forecasting

Academic research project (2021) on forecasting market liquidity from high-frequency BTC/USD transaction data with recurrent neural networks.

The notebook starts from raw trade-level data, builds a time-series representation of the market, and trains an LSTM model for forecasting. The repository also includes the accompanying project report.

## Tech

Python · pandas · NumPy · Matplotlib · PyTorch · LSTM · Jupyter

## Data and modeling

The notebook works with BTC/USD trades from Bitstamp. The original dataset contains roughly 1.45 million transactions for Q4 2020 and includes timestamps, prices, trade amounts, and buy/sell direction.

The modeling workflow includes:

1. transaction-data cleaning and exploratory analysis;
2. time-series construction and feature preparation;
3. sequence generation for recurrent modeling;
4. a custom PyTorch LSTM model;
5. training with MSE loss and Adam;
6. evaluation and visualization of forecasts.

## Files

- `Liquidity forecasting.ipynb` — complete research workflow from raw transactions to LSTM forecasting;
- `Отчёт_Ловчикова_Юлия.pdf` — project report.

## Research context

This is an archived academic project. The original external dataset is not stored in the repository, so the notebook should be read primarily as evidence of the modeling and research workflow rather than as a plug-and-play package.
