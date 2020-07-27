## Summer Project: TECHNICAL ANALYSIS OF NIFTY 50 - Finance and Analytics Club, IIT Kanpur 

The objective of the project is to get familiar with the concepts of the applications of technical analysis (mainly related to building and testing the validity of stock indicators) using OLS Linear Regression in Python.

### Task-1 <br/>
Timeline: 28th April 2020 to 12th May 2020 <br/>

Objectives:

* Get familiar with Python libraries like Numpy, Pandas, and Matplotlib.
* Import stock data in either using an API or Yahoo Finance.
* Knowing about the fundamental of statistics, confidence intervals, and probability distribution.
* Data visualization of the  Simple Moving Average (SMA) through Matplotlib and Seaborn.

Concepts used:

* Import stock data from Yahoo finance – Copy the link from Yahoo finance and extracting through the read_csv() method and dropping unnecessary columns like Open, Low, High, and Volume using the drop()  method. 
* Checking the descriptive statistics – Methods like info(), describe(), mean(), and std(). Also checking for any stock splits.
* Plotting the daily return – Transforming the Close or Adj close into percentage change (new column) using pct_change() and then using Seaborn to plot the KDE distribution of the daily returns.
* Calculating the SMA – Methods like .rolling() and mean() to calculate the SMA of the last X days.
* Plotting the SMA and Closing Price to check for the cross-overs – Plotting the line graph using plot() of the closing price and the SMA, titling and scaling the axis, and attributing through other key features of Matplotlib


Learnings:

* Understanding the descriptive statistics from the stock data, which is related to the mean, variance, and how the distribution of the daily percentage returns.
* Finding the crossovers (bullish and bearish) points by visualizing the data.

### Task-2

Timeline: 13th May 2020 to 7th June 2020

Objectives:

* Import stock data in either using an API or Yahoo Finance.
* Use 3 technical indicators to visualize our stock data and identify bullish and bearish crossovers - SMA, MACD, Bollinger Bands
* Data visualization of the indicators through Matplotlib and Seaborn.
* Calculating mean absolute return for the next 10 days.

Concepts used:

* Import stock data from Yahoo finance – Copy the link from Yahoo finance and extracting through the read_csv() method and dropping unnecessary columns like Open, Low, High, and Volume using the drop()  method. 
* Visualizing the data using graphs - Plotting the line graph using plot() of the closing price and the indicator used.
* Calculate and interpret the RSI – Using for loop to find the ratio of the average gains and average losses in the past  14 days and calculate the RSI .Give bullish signal when RSI<30% and bearish when RSI>70%
* Calculate and interpret the MACD – Use .ewm() and mean() function to calculate MACD.Use this to calculate the signal line. Give a bullish signal when MACD crosses the signal line and bearish signal when the signal line crosses MACD.
* Calculating the SMA – Methods like .rolling() and mean() to calculate the SMA of the last X days. Give a bullish signal when SMA crosses the closing price and bearish signal when closing price crosses SMA.
* Calculate mean absolute return - Use for() loop and abs() function to calculate the mean absolute return for the next 10 days.

Learnings:

* Finding the crossovers (bullish and bearish) points by visualizing the data.
* Using various indicators like SMA, RSI and MACD to identify bullish and bearish crossovers and accordingly prepare a trading strategy.
* Significance and calculation of the mean absolute return.

# Task-3

Timeline: 8th June 2020 to 28th June 2020

Objectives:

* Develop an OLS linear regression model in Python with mean absolute return as the dependent variable and each of the three indicators as the independent variable. Separate regression equations for separate indicators.
* Develop an OLS multiple linear regression model using Python with absolute return as the dependent variable and all our indicators as the independent variable.
Concepts used:
* Developing OLS linear regression model - Use python library statsmodels.formula.api to develop OLS linear regression model and OLS multivariate linear regression model
* Testing the significance of the model - Use model.summary() and check the value of R2 and P(F) to check the validity of our model.
* Testing the significance of our variables - Use model.summary() and check the value of P(t) to check the validity of our variables.
* Find the coefficients and intercept of our model - Use model.summary() to find the value of coefficients.

Learnings:

* Building, testing, and interpreting the OLS linear regression model.
* Building and testing our OLS multiple linear regression model.

