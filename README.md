# portfolio-optimization-and-LSTM
## Portfolio Optimization and Stock Price Prediction--- S&P500 stock data
Project completed for academic, self-learning, and hobby purposes. 
Presented in the form of Jupyter notebooks.

## Overview
This project is divided into two parts:

**1. Portfolio Optimization**
* Retrieves a list of companies included in the S&P 500 and gathers basic information as well as historical stock price data for them.
* Calculates daily returns based on closing prices using a simple return formula.
* Saves the data to dataframes and CSV files.
* Connects to a PostgreSQL database and imports data tables.
* Conducts portfolio optimization and outputs suggested portfolio component weights considering two scenarios: risk minimization and maximization of the Sharpe ratio.
* Plots the Efficient Frontier.

*Tools: pandas, numpy, time, datetime, functools, yfinance, matplotlib, scipy, sqlalchemy*

**2. Stock Price Prediction with LSTM model**
* Historical closing price data for the selected stocks will be gathered from cvs saved by the means of the first part of this project (*Portfolio Optimization file*).
* Using the Keras library, we will construct LSTM models capable of learning from past trends and patterns in the stock data.
* The LSTM models will be trained on the historical data to capture temporal dependencies and understand the underlying patterns in the stock prices.
* Once trained, the LSTM models will be used to generate predictions for future stock prices. We will evaluate the performance of our models using RMSE.

*Tools: pandas, numpy, matplotlib, seaborn, sklearn, keras*

## Motivation
This project underscores the significance of data-driven decision-making in investment strategies, leveraging historical data and mathematical models. It's an exploration of the code's functionality, serving as a tool for hypothetical investors and providing suggestions upon which they can reconsider their investment strategy. Please note that this work is only for self-learning purposes and is not to be considered investment advice.

## Credits
This project would not have been possible without the knowledge gained from the following articles:
* https://www.analyticsvidhya.com/blog/2018/10/predicting-stock-price-machine-learningnd-deep-learning-techniques-python/
* https://towardsdatascience.com/time-series-forecasting-with-recurrent-neural-networks-74674e289816
* https://www.kaggle.com/code/faressayah/stock-market-analysis-prediction-using-lstm
* https://www.simplilearn.com/tutorials/machine-learning-tutorial/stock-price-prediction-using-machine-learning






