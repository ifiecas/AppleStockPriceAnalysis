# Apple Stock Price Analysis and Visualization

## Overview
This project focuses on visualizing and analyzing Apple (AAPL) stock price data using Python. The visualization includes interactive candlestick charts, line plots, and bar charts powered by Plotly. The stock data is fetched using the yfinance API, providing real-time and historical financial data.

## Code Reference & Attribution
This project was developed following the tutorial on Time Series Analysis using Python by Aman Kharwal at The Clever Programmer:
- Tutorial Link: [Time Series Analysis using Python](https://thecleverprogrammer.com/2022/01/17/time-series-analysis-using-python/)
- Author: Aman Kharwal
- Website: The Clever Programmer
- Date: January 17, 2022

The original tutorial has been modified and enhanced with:
- Updated code for current Python libraries
- Additional visualizations
- Customized for Apple (AAPL) stock analysis
- Enhanced date labeling and formatting

## Features
- **Data Collection**: Utilizes `yfinance` API to fetch Apple stock data directly from Yahoo Finance
- **Interactive Visualizations**: 
  - Candlestick chart with range slider and time period selectors
  - Line plots showing closing price trends
  - Bar charts for volume analysis
- **Time Range Selection**: Built-in date range selectors (1M, 6M, YTD, 1Y, ALL)
- **Price Indicators**: Displays key price points including:
  - Opening price
  - Closing price
  - High price
  - Low price
  - Trading volume

## Technologies Used
- **Python 3.x**
- **Libraries**:
  - `yfinance`: For fetching stock market data
  - `plotly`: For creating interactive visualizations
  - `pandas`: For data manipulation and analysis
  - `datetime`: For handling date operations

## Installation
```bash
pip install yfinance
pip install plotly
