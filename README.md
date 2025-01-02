# 📊 Stock Excess Returns Regression

This repository contains Python code and analysis for performing regression modeling on financial data, specifically focusing on excess returns for multiple financial assets. The dataset used includes market data for various stock tickers, including XOM, Mkt-RF, SMB, and HML, and aims to identify the relationship between these variables using Ordinary Least Squares (OLS) regression models.

## 🚀 Project Overview

The primary objective of this project is to analyze and model the relationship between different financial factors (Market Excess Returns, SMB, HML) and the excess returns of stocks using regression analysis. This will help in understanding the influence of market risk factors and individual stock characteristics on their performance.

## 🗃️ Data

The dataset used in this project includes financial data such as:
- **XOM**: Excess returns for ExxonMobil.
- **Mkt-RF**: Market excess returns.
- **SMB**: Small-minus-big factor.
- **HML**: High-minus-low factor.
- **Additional Factors**: Market factors such as size and value premiums.

## 🧮 Methodology

### Regression Models:
1. **OLS Regression**: The project uses Ordinary Least Squares (OLS) regression to model the excess returns. 
2. **Factors Analyzed**: The primary factors used in the regression models are Market Excess Returns (Mkt-RF), SMB (size factor), and HML (value factor).
3. **Evaluation**: The models are evaluated based on R-squared values, p-values, and the F-statistic to determine the significance of the factors.

### Analysis:
- **Model 1: XOM Excess Returns**: Analysis of excess returns for ExxonMobil stock against the market factors.
- **Model 2: Market Excess Returns**: Regression of market excess returns on market factors.
- **Model 3: SMB Excess Returns**: Regression of small-minus-big factor excess returns.
- **Model 4: HML Excess Returns**: Regression of high-minus-low factor excess returns.

## 📈 Key Results

- **XOM Regression**: A significant relationship between the Mkt-RF and XOM excess returns, with a coefficient of 0.7354 (p-value < 0.05).
- **Mkt-RF Regression**: A near-perfect fit with R-squared of 1.0, indicating a strong relationship between Mkt-RF and its own factors.
- **SMB and HML Regression**: Both SMB and HML models show strong relationships with R-squared values close to 1.0.

## 🧩 Requirements

- Python 3.x
- pandas
- statsmodels
- numpy
- matplotlib
- seaborn

