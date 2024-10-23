# TCS Stock Price Trend Analysis and Visualization

## Overview

This project analyzes and predicts the stock price trends of Tata Consultancy Services (TCS) using Long Short-Term Memory (LSTM) neural networks. The model is trained on historical stock data obtained from Yahoo Finance and visualizes the predictions against actual prices. 

## Features

- **Data Collection:** Fetches historical stock prices using the `yfinance` library.
- **Data Preprocessing:** Cleans the data, calculates moving averages, and scales it for LSTM input.
- **LSTM Model:** Implements an LSTM model for predicting future stock prices.
- **Visualization:** Displays stock price trends and prediction accuracy through plots.

## Requirements

- Python 3.x
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `yfinance`
  - `tensorflow`
  - `sklearn`

## Usage
- Load the data by specifying the stock ticker: data = load_data('TCS.NS')
- Train the model: model.fit(x_train, y_train, epochs=100)
- Make predictions and visualize results:
  - 'y_pred = model.predict(x_test)'
  - 'plot_results(y_test, y_pred)'
- Evaluate the model:
  - 'print("Mean Absolute Error:", mae)'
  - - 'print("R2 Score:", r2)'
## Results
- Visual comparison of predicted vs. actual prices.
- Performance metrics including Mean Absolute Error (MAE) and R² score.
## Future Improvements
1.Experiment with different architectures and hyperparameters.
2.Incorporate additional features like trading volume or other technical indicators.
3.Expand the model to analyze other stocks and market indices.
