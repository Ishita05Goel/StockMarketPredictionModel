LSTM Stock Price Forecasting 📈

A Python project that uses LSTM (Long Short-Term Memory) to predict future stock prices based on historical data.

Features

Predicts Adjusted Close price using historical data.

Uses Adj Close and Volume as input features.

Performs one-step test prediction and long-term iterative forecasting (~5 years).

Visualizes historical vs forecasted prices.

Saves predictions to a CSV file.

Requirements

Python 3

Libraries: numpy, pandas, matplotlib, scikit-learn, tensorflow

Install dependencies:

pip install numpy pandas matplotlib scikit-learn tensorflow

How to Use

Place your CSV file with Date, Adj Close, Volume columns.

Update the FILE variable in the script with your CSV path.

Run the script:

python lstm_stock_forecast.py


The forecast will be saved as adj_close_5yr_forecast.csv and a plot will be shown.
