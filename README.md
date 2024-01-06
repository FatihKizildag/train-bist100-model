

# BIST100 Next Candlestick Prediction


## Overview

This project predicts the next candlestick pattern for BIST100 (Borsa Istanbul 100) stocks using historical stock price data from Yahoo Finance. Candlestick patterns are vital in technical analysis for forecasting price movements. The project involves feature extraction, machine learning model training (Random Forest, LightGBM, and CatBoost), and evaluating their performance.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/FatihKizildag/train-bist100-model.git
   ```

2. Install the required libraries:

   ```bash
   pip install catboost
   pip install git+https://github.com/optuna/optuna.git
   conda install -c conda-forge optuna
   ```

3. Download the stock data using the provided by yfinance lib:

   ```bash
   yf.download(symbol, start=starDate, end=endDate, interval=interval)
   ```

4. Train the machine learning models:

   Deatils are in the code

## Data Acquisition

Downloads historical stock price data for BIST100 stocks from Yahoo Finance using the `yfinance` library. The data is cleaned and processed to create candlestick charts.

## Machine Learning Models

Project focuses on feature engineering, training, and evaluating machine learning models. The models include Random Forest, LightGBM, and CatBoost. The performance metrics such as Precision, Recall, and F1 Score are reported.

## Features

- Candlestick charts for visualizing historical stock price data.
- Next candlestick pattern prediction using machine learning models.
- Feature extraction from stock price data.
- Evaluation of machine learning model performance.

## Results

The top-performing machine learning models for each BIST100 stock, along with their F1 scores, are displayed in the results section. The results are based on the evaluation of each model's ability to predict the next candlestick pattern.

## Future Work

- Fine-tuning hyperparameters for better model performance.
- Exploring additional feature engineering techniques.
- Expanding the scope to include more BIST100 stocks.

