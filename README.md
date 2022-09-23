# Analysis-of-NSE-Stock-Exchange-Dataset

1. ABSTARCT:
This study comprises of the variation of market prices of various companies over a particular time period.
The National Stock Exchange located in Mumbai, India has a market capitalization of $ 1.41 Trillion. The
National Stock Exchange offers trading and investment in equities, derivatives and debt. NIFTY 50, the
index of National Stock Exchange, is used as a measure of Indian capital markets by many investors. This
dataset comprises of values like opening and closing market prices, highest and lowest market prices, last
market price and the total traded values and quantities of various companies. Variables like Total Traded
Quantity, Total Traded Values and Total Trades depend on variables like HIGH, CLOSE, LAST, OPEN, LOW
and PREVCLOSE.

2. INTRODUCTION:
Stockbrokers and traders buy and sell shares of stock, bonds and other securities in a stock Exchange. For
trading a security, it must be listed on the stock exchange. Participants in the market include retail
investors, mutual funds, banks, insurance companies and hedge funds. The roles of stock exchange are
raising capital for business, mobilizing savings for investment, facilitating company growth, profit sharing,
corporate governance and creation of investment opportunities.

3. Study of the stock-market prices of listed in National Stock Exchange:

3.1 Overview:
The aim of this study was to analyze the various market prices of the National Stock Exchange of the
companies listed. The analysis reveals that the mean of total traded quantities is 698380. Also, it seems
that the average of total trades is 5014. (
https://en.wikipedia.org/wiki/National_Stock_Exchange_of_India#Markets )

3.2 Data:
For this analysis, we collected data from https://www.kaggle.com/minatverma/nse-stocks-data. This
dataset comprised a big list of companies and they were classified under the column “SERIES” as per the
series of equity values. On descriptive analysis of the dataset, it was found that the values of equity are EQ,
BE and IQ. Also, the analysis reveals that, the average values of Opening and Closing Market prices turn out
to be 538.017041 and 540.578336 respectively.
The data is of National Stock Exchange of India’s stock listings for each trading day of 2016 and 2017. The
columns of the dataset are described below:
SYMBOL: Symbol of the listed company. SERIES: Series of the equity. Values are [EQ, BE, BL, BT, GC and IL]
OPEN: The opening market price of the equity symbol on the date. HIGH: The highest market price of the
equity symbol on the date. LOW: The lowest recorded market price of the equity symbol on the date.
CLOSE: The closing recorded price of the equity symbol on the date. LAST: The last traded price of the
equity symbol on the date. PREVCLOSE: The previous day closing price of the equity symbol on the date.
TOTTRDQTY: Total traded quantity of the equity symbol on the date. TOTTRDVAL: Total traded volume of
the equity symbol on the date. TOTALTRADES: Total trades executed on the day.

3.3 MODEL:
The model was carried out to test the H1 Hypothesis.
The result of the model tells us that the all the independent variables like OPEN, HIGH, CLOSE, LOW, LAST,
PREVCLOSE have a great influence on the dependent variables. This reveals that the Total Traded Values
and Total Traded Quantities vary greatly based on these independent variables.

3.4. Results:
The result of the empirical study reveals that, there is a strong effect of variables like LOW, HIGH, CLOSE,
LAST, OPEN on the other variables like TOTTRDQTY, TOTTRDVAL. The regression model produced the value
of p-value < 0.05.

4. Conclusion:
This study helped us to understand the range of market prices within which the shares of each company
varied. It looks like, the closing market prices, lowest and highest market prices, and the last traded price
of every company prove to be statistically significant.

5. References:
1. https://en.wikipedia.org/wiki/Stock_exchange
2. https://en.wikipedia.org/wiki/National_Stock_Exchange_of_India#Markets
3. https://www.kaggle.com/minatverma/nse-stocks-data
4. https://en.wikipedia.org/wiki/Stock_market
5. https://nseindia.com/
