# StockTrend

## Project Overview

This project involves the analysis and modeling of time series data from the Nifty 50 stock market. Using historical stock prices from **ICICIBank**, the project aims to extract insights and build predictive models for stock price trends. The analysis includes data preprocessing, visualization, feature engineering, and predictive modeling using various time series techniques.

## Features

- **Data Loading**: Integration of historical stock market data for **ICICIBank**.
- **Exploratory Data Analysis (EDA)**: Visualization of stock price trends, moving averages, and other key metrics.
- **Time Series Modeling**: Application of models like ARIMA, Prophet, or LSTM for stock price prediction.
- **Evaluation Metrics**: Use of metrics like RMSE and MAE to evaluate model performance.

## Datasets

The datasets used in this project are sourced from Kaggle and include:

- Individual company stock data for **ICICIBank** (`ICICIBANK.csv`).
- Metadata about stocks (`stock_metadata.csv`).
- Aggregated data (`NIFTY50_all.csv`).

The data spans from **1st January 2000 to 30th April 2021** and includes daily stock price history and trading volumes for ICICIBank from the Nifty 50 index on the NSE (National Stock Exchange) India.

## Tools and Libraries

The project utilizes the following tools and libraries:

- **Python Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- **Time Series Libraries**: `statsmodels`, `fbprophet`, `tensorflow` (if applicable)
- **Environment**: Jupyter Notebook for development and visualization

## Project Workflow

1. **Data Importation**: Load the datasets into Pandas DataFrames.
2. **Data Cleaning**: Handle missing values, outliers, and other inconsistencies.
3. **EDA**:
   - Visualize stock trends and calculate moving averages.
   - Analyze seasonality and trends.
4. **Feature Engineering**: Generate lag features, rolling averages, and other derived features.
5. **Modeling**:
   - Apply time series models such as ARIMA or SARIMA.
   - Test advanced techniques like LSTMs for long-term predictions.
6. **Evaluation**: Use metrics such as RMSE, MAE, and MAPE for validation.

## Results

- Visualizations highlighting stock price trends, seasonality, and anomalies.
- Predictive models with quantified performance metrics.
- Insights into stock market patterns and recommendations for future studies.

