# MSFT-Stock-Prediction
# Microsoft (MSFT) Stock Price Forecasting: ARIMA vs. LSTM

This project analyzes and forecasts Microsoft (MSFT) daily closing stock prices using time series models in Python. It compares the classical ARIMA approach with an advanced LSTM neural network to evaluate prediction accuracy.

## Project Overview

- **Data sourced** from Yahoo Finance (daily MSFT closing prices)
- **ARIMA modeling** for statistical time series forecasting
- **LSTM deep learning** sequence modeling for capturing complex market dynamics
- **Model validation** with out-of-sample test set
- **Performance metrics:** RMSE, MAE
- **Result:** LSTM model achieved a Root Mean Squared Error (RMSE) **65% lower than ARIMA**, highlighting its strength for financial forecasting.

## Files

- `MSFT_forecasting.ipynb`: Main Jupyter Notebook with full workflow, code, and output
- `README.md`: This project summary and usage notes

## How to Use

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Run all cells sequentially to download data, preprocess, train models, evaluate, and visualize results.
3. Review model comparison plots and RMSE/MAE outputs to interpret forecasting performance.

## Key Python Libraries

- `pandas`, `numpy` for data handling
- `matplotlib`, `seaborn` for visualization
- `statsmodels` for ARIMA modeling
- `keras` for LSTM neural network
- `sklearn` for scaling and metrics

## Results and Insights

- **ARIMA:** Efficient for linear, stationary time series modeling
- **LSTM:** Superior performance for non-linear, complex patterns (MSFT stock), with RMSE 65% lower than ARIMA on test set

## Author

Purohit Yug

---


