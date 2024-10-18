# Italian Stock Portfolio Analysis and Optimization in Excel


# Project Overview
This Excel project focuses on analyzing and optimizing a portfolio of 8 Italian stocks, covering the period from January 2020 to December 2023. The goal is to calculate daily returns, perform portfolio optimization using the Sharpe ratio, and compare the portfolio's performance with the FTSE MIB, the Italian stock market index.

Data Source
Stocks Analyzed:

ERG
MONC (Moncler)
RACE (Ferrari)
UCG (Unicredit)
ISP (Intesa Sanpaolo)
STLAM (Stellantis)
SFER (Salvatore Ferragamo)
FCT (Fincantieri)
# Data Period: January 2020 - December 2023

Data Imported Using:
The Excel STOCKHISTORY function, fetching the daily data for Closing Prices and Volume


Steps Performed
Data Import:
Stock data for the 8 companies was imported using the STOCKHISTORY function. The daily closing prices and trading volumes were fetched over the specified time period.

Daily Returns Calculation:
The daily returns for each stock were calculated as the percentage change in the closing prices between consecutive days.

Sharpe Ratio Optimization:

Standard Deviation: The standard deviation of the daily returns was computed for each stock to measure volatility.
Portfolio Standard Deviation: A weighted portfolio standard deviation was calculated, considering the weights of each stock in the portfolio.
Efficient Frontier and Monte Carlo Simulation:
Through Monte Carlo simulation, various combinations of return and standard deviation were generated. The Efficient Frontier was plotted, and the optimal portfolio weights were determined.

​
This ratio was maximized to identify the optimal stock weights in the portfolio.
# Benchmark Comparison:
The aim is to benchmark the portfolio against the FTSE MIB index, allowing for a comparison of risk and return characteristics through a Tableau dashboard.
