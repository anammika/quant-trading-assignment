#Quantitative Trading Strategy Project#
##Overview##

This project demonstrates an end-to-end quantitative trading strategy pipeline built using Python.
The objective of the project is learning and understanding how algorithmic trading systems are structured, from data preparation to strategy evaluation and intelligent trade filtering.

This project is educational and not intended for live trading.


Project Objectives

Understand the workflow of a quantitative trading system

Learn data preparation and feature engineering for financial data

Apply market regime detection

Design and backtest a rule-based trading strategy

Improve strategy performance using a lightweight ML-based trade filter

Project Workflow

Data Preparation

Feature Engineering

Market Regime Detection

Trading Strategy Design

Strategy Backtesting

Machine Learning / Statistical Trade Filtering


Dataset Description

The project uses dummy intraday 5-minute market data representing:

NIFTY Spot prices

NIFTY Futures prices

NIFTY Options data (Call & Put)

The data is created to simulate realistic market behavior for learning purposes.



Notebook Explanation
1. Data Preparation (01_data_preparation.ipynb)

Created dummy intraday market data

Cleaned and aligned timestamps

Merged spot, futures, and options data

Saved cleaned dataset for further analysis


Feature Engineering (02_feature_engineering.ipynb)

Generated technical and market features such as:

EMA (5, 15)

Returns

Futures basis

Put-Call Ratio (PCR)

Average implied volatility

Converted raw data into model-ready numerical features
