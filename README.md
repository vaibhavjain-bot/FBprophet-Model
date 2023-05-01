

# Stock Price Prediction with Prophet

This repository contains a Python script that uses the Prophet library to predict the closing prices of a given stock. In this example, we use Apple (AAPL) as our target stock, but you can modify the code to use any other stock that is supported by the yfinance library.

## Usage

The script will retrieve the historical stock data for the past 7 years, split it into a training set and a test set, and use the Prophet model to predict the closing prices for the test set. It will then plot the actual and predicted closing prices using both matplotlib and plotly. Finally, it will create a future dataframe for 365 days and use the model to predict the closing prices for this time period, which it will then plot using both matplotlib and plotly.

You can modify the script to use a different stock or time period by changing the arguments to the `yf.Ticker()` and `history()` functions, respectively. You can also modify the model hyperparameters by changing the arguments to the `Prophet()` function.

## License

This code is released under the MIT License. Feel free to modify and use it for your own purposes. If you find any bugs or issues, please submit them to the issue tracker on Github.
