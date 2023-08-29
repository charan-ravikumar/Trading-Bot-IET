# TradingBot

We designed an LSTM bidirectional model for future stock price prediction and made use of python libraries like pandas, NumPy, Keras, and sklearn. We initially trained the model on a smaller dataset. Yfinance API is used to get data. First, converted prices and volumes into price returns/percentage changes then min-max normalization is applied to all price and volume data, making our data range from 0–1. After having trained for 200 epochs we obtained the accuracy of 80%.
