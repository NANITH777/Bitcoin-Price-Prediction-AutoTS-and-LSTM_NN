# Bitcoin Price Analysis and Forecasting

This repository contains a Python script for analyzing and forecasting Bitcoin prices using various data science techniques. The script performs data extraction, visualization, correlation analysis, and time series forecasting. Additionally, it uses machine learning techniques to predict future Bitcoin prices.

## Table of Contents

- [Installation](#installation)
- [Features](#features)
- [Data](#data)
- [Visualization](#visualization)
- [Correlation Analysis](#correlation-analysis)
- [Time Series Forecasting](#time-series-forecasting)
- [Machine Learning Prediction](#machine-learning-prediction)
- [Results](#results)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/NANITH777/Bitcoin-Price-Prediction-AutoTS-and-LSTM_NN.git
   cd bitcoin-price-analysis
   ```

## Features

- **Data Extraction:** Fetch historical Bitcoin price data from Yahoo Finance.
- **Visualization:** Generate candlestick charts for price analysis.
- **Correlation Analysis:** Compute and visualize the correlation matrix of different financial metrics.
- **Time Series Forecasting:** Use the AutoTS library to predict future Bitcoin prices.
- **Machine Learning Prediction:** Build and train an LSTM model to predict Bitcoin closing prices.

## Data

The script fetches Bitcoin price data from Yahoo Finance, covering the last two years from the current date. The data includes the following columns:
- Date
- Open
- High
- Low
- Close
- Adj Close
- Volume

## Visualization

The script generates a candlestick chart to visualize the price movement of Bitcoin over time. The chart is saved as `analysis.png` and displayed in the output.

## Correlation Analysis

The script computes the correlation matrix for the financial metrics and visualizes it using a heatmap. This helps in understanding the relationships between different variables.

## Time Series Forecasting

The script uses the AutoTS library to perform time series forecasting. It forecasts Bitcoin prices for the next 30 days and saves the forecast data to `30daysPrediction.csv`.

## Machine Learning Prediction

The script builds an LSTM model to predict Bitcoin closing prices based on the historical data. It splits the data into training and testing sets, trains the model, and evaluates its performance.

## Results

- The candlestick chart and correlation matrix provide insights into the historical price movement and relationships between variables.
- The forecasted Bitcoin prices for the next 30 days are saved in `30daysPrediction.csv`.
- The LSTM model predicts the closing price based on the provided input features.
