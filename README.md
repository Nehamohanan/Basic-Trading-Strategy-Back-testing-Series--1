# Basic-Trading-Strategy-Back-testing-Series-1
Basic Trading Strategy Back testing Series -1( Three Moving Average Crossover Long-Short)

<br>
Introduction

In statistics, a moving average (rolling average or running average) is a calculation to analyze data points by creating a series of averages of different selections of the full data set. It is also called a moving mean or rolling mean and is a type of finite impulse response filter. Variations include: simple, cumulative, exponential or weighted forms.

Simple Moving Average (SMA): This is the most basic type of moving average, which calculates the average price of an asset over a set number of periods by simply summing up the prices and dividing by the number of periods. 

Methodology

We are using the following conditions for backtesting the strategy:

Using three simple moving averages of 30, 60, and 110.<br>
Go long when the price crosses above all three moving averages.<br>
Exit the long position when the price crosses below any of the three moving averages.<br>
Go short when the price crosses below all three moving averages.<br>
Exit the short position when the price crosses above any of the three moving averages.<br>

Dataset Used<br>
Twenty years daily data of Nifty50 is used for backtesting the above strategy starting from '2001-01-01'.
