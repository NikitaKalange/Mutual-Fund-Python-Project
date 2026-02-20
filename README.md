# Mutual-Fund-Python-Project

Project Overview - 

This project is a Python-based Mutual Fund Portfolio Simulator where I built a simple system to:
  Analyze historical stock data
  Calculate returns and risk
  Create different portfolio combinations
  Identify the best portfolio using risk-adjusted returns

Dataset Used - 

The dataset contains historical closing prices of NIFTY 50 stocks.
Each column represents a stock, and each row represents daily closing prices.
From this data, I calculated daily returns and annualized metrics for portfolio analysis.

Tools & Libraries Used - 

Python, Pandas, NumPy, Matplotlib, Seaborn
These libraries were used for data cleaning, calculations, simulations, and visualizations.

Project Workflow ---> 

1. Data Preparation : 
  Loaded historical stock price data
  Converted date column into datetime format
  Handled missing values
  Calculated daily returns

2. Feature Engineering : 
  Calculated Annualized Return
  Calculated Annualized Volatility (Risk)
  Created Risk-Return comparison table

3. Exploratory Data Analysis (EDA) : 
  Correlation Heatmap (to understand diversification)
  Risk vs Return Scatter Plot
  This helped in understanding how different stocks behave and how they are related to each other.

4. Portfolio Construction : 
  Selected multiple stocks
  Assigned weights to each stock
  Calculated:
    Portfolio Return
    Portfolio Risk (Volatility)
  This step helped in understanding how combining stocks affects overall performance.

5. Monte Carlo Simulation (20 Portfolios) : 
  Instead of testing only one allocation, I generated 20 random portfolio combinations.
  For each portfolio, I calculated:
    Expected Return
    Risk
    Sharpe Ratio
  The portfolio with the highest Sharpe Ratio was selected as the optimal portfolio.


Final Outcome -

After running the simulation, I identified the portfolio with the best Sharpe Ratio.
This portfolio provides:
  Better risk-adjusted returns
  Balanced diversification
  Optimized allocation among selected stocks
    
