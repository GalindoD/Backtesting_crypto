# Backtesting for trading strategies in crypto

## Libraries used
Yfinance, backtrader, matplotlib, numpy, plotly, talib

## Trading strategies tested
On this first implementation the only indicators used are MACD and MA. 
The strategies are a combination of parameters for these two indicators

##How it works
The fisrt thing is to get the data from yfinance API, specifying the ticker and timeframes
Then, it creates the DataFrame adding the indicators columns calculated with the talib library
After that, the buy and sell signals are calculated according to the strategy selected
At the end, the dataframe is presented and two plots are created. One for the price and indicators; and the other one is for the accumulated returns

##Example of a Result Dataframe
![Screenshot of a dataframe example](https://github.com/GalindoD/Backtesting_crypto/blob/main/DF%20image.png?raw=true)

##Example of the graphs
![Screenshot of thePrice graph, with the MAs, MACD and Buy/Sell signals](https://github.com/GalindoD/Backtesting_crypto/blob/361a9222331f102ec170681829cbfe98ec18b94d/Price%2BMA%2BMACD.png)

![Screenshot of the full strategy performance](https://github.com/GalindoD/Backtesting_crypto/blob/361a9222331f102ec170681829cbfe98ec18b94d/Strategy%20performance.png)




