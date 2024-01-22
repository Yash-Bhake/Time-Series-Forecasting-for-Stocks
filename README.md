## Time Series Forecasting for Stocks

In the given code, I have started with visualising the time series, - one year stock prices for TSLA (TESLA Inc).
Used acf, pacf to get arma orders, and decided to use ARIMA(1, 1, 1) as one mean was varying, one difference was required too for makin gthe data stationary.
Trained model on 11 month, tested on one month, got rmse of around 5, on rolling forecasting
Isolated the residuals, and implemented an ARIMA(1, 1, 1) model on it as well, and then added the results of the error forecast to the test data predictions.
