# Stock Price Prediction

This project aims to predict the stock prices of Reliance Industries Limited using an LSTM (Long Short-Term Memory) model. The dataset spans from January 1, 2010, to June 15, 2024. The model is trained on the historical closing prices and predicts future prices.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/stock-price-prediction.git
    cd stock-price-prediction
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Ensure you have `yfinance` and `tensorflow` installed:
    ```bash
    pip install yfinance tensorflow
    ```

## Usage

1. Run the script to train the model and make predictions:
    ```bash
    python stock_price_prediction.py
    ```

2. The script will:
    - Fetch historical stock data from Yahoo Finance.
    - Visualize the closing price history.
    - Train an LSTM model on the historical data.
    - Predict future stock prices.
    - Visualize the predictions.

## Results

The model's performance is evaluated using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Mean Absolute Percentage Error (MAPE). Here are the results:
- **MAE:** 34.36
- **RMSE:** 44.48
- **MAPE:** 1.45%

The predicted stock prices for the future are plotted alongside the historical prices for comparison.

## Future Work

- Improve the model by tuning hyperparameters.
- Incorporate additional features like trading volume, market indicators, etc.
- Test with other machine learning models and compare their performance.

