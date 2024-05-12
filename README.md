# NSEI Stock close price prediction


## Project summary

The objective of this project is to analyze the closing stock prices of National Stock Exchange of India Limited (NSE). It is one of the leading stock exchanges in India, based in Mumbai. NSE is under the ownership of various financial institutions such as banks and insurance companies. It is the world's largest derivatives exchange by number of contracts traded and the third largest in cash equities by number of trades for the calendar year 2022. It is the 7th largest stock exchange in the world by total market capitalization, as of January 2024. NSE's flagship index, the NIFTY 50, a 50 stock index is used extensively by investors in India and around the world as a barometer of the Indian capital market.

To predict the stock's closing price, it will be acheived by four models namely Linear Regression, Ridge_regression, Lasso_regression, and Random Forest model. The model was trained using the historical stock price data and various features such as mean of Open, High and Low faetures. Additional features were engineered by taking lags to capture the temporal trends and patterns in the data. The performance of the model was evaluated using metrics like MSE (Mean Squared Error) because we used LeaveOneOut cross validation so we can't use R2 score.

The analysis aimed to uncover any patterns or changes in stock prices.

## Objective

The ultimate business objective is to use the regression model to provide accurate predictions of the closing price of NSEI stock, enabling stakeholders to make well-informed investment decisions, manage risks effectively, optimize portfolios, Early warning systems to alert any fraud cases and align investment strategies with financial goals.

## Information about dataset

1. ***Date***: The date when the stock data was recorded.
2. ***Open***: The date when the stock data was recorded.
3. ***High***: The highest price the stock reached during the trading day.
4. ***Low***: The highest price the stock reached during the trading day.
5. ***Close***: The price of the stock when the market closed on that particular date.
6. ***Adj Close***: The adjusted closing price reflects the stock's value after accounting for any corporate actions such as dividends, stock splits, or mergers.
7. ***Volume***: The price of the stock when the market closed on that particular date.


**Adjusted Closing** price: The adjusted closing price is a modification of a stock's closing price that accounts for any corporate actions that may affect the stock's value. These corporate actions can include dividends, stock splits, spin-offs, and mergers.<br>For example, when a company pays a dividend, the stock's price typically decreases by the amount of the dividend after the dividend is paid. To accurately track the stock's performance over time, analysts adjust historical closing prices to reflect these changes. This adjustment ensures that historical price charts and calculations accurately represent the stock's value, accounting for all relevant corporate actions.<br>In summary, the adjusted closing price is the closing price of a stock after accounting for any corporate actions that may affect its value, providing a more accurate representation of its performance over time.
