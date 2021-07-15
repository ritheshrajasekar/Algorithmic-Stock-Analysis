# Algorithmic-Stock-Analysis

In this project, I perform stock data analysis for Microsoft and Facebook using various technical indicators. 
Various libraries such as BeautifulSoup(for data scrapping), pandas/numpy(for data cleaning), matplotlib(for data visualization), 
and yfinance(for making API requests) were used. 

Specfically, the Relative Strength Index(RSI), Simple Moving Averages (SMA), 
and Moving Average Convergence Divergence (MACD) were used to algorithmically trade the stocks.
Using each indicator seperately, the program graphically displays when a buy and sell signal would be given. 
The same time period of 11 months and two stocks were used with all 3 technical indicators in order to standarize the results. 


Trading based off RSI proved to be the most effective in comparison to the other two indicators as it yielded the highest amount of profit for 
both stocks in the 11 month time period. This correlates with the fact that SMA is usually used as general trend line as the SMA takes relatively long
to adjust to a current trend. In addition, the MACD is known to often have false positive signals that can impact its accuracy.
However, the indicators are best used together in order to corroborate buy and sell signals which I hope to implement in the future.
