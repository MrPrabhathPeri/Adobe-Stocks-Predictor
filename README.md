# Adobe Stock Price Predictor

## Overview
This project uses machine learning to predict Adobe stock prices. The model is built using historical stock price data to forecast future prices.

## Dataset
The dataset used for this project is an Adobe stock price dataset found on Kaggle. It includes the following columns:
- **Date**: The date of the record
- **Open**: The opening price of the stock
- **High**: The highest price of the stock
- **Low**: The lowest price of the stock
- **Close**: The closing price of the stock
- **Adj Close**: The adjusted closing price of the stock
- **Volume**: The trading volume of the stock

## Usage
1. **Data Preparation**: The dataset is loaded and preprocessed to be used with a Long Short-Term Memory (LSTM) model.
2. **Model Training**: The LSTM model is trained on historical stock price data.
3. **Prediction**: The model predicts future stock prices based on the trained data.

## Requirements
- Python 3.x
- Pandas
- NumPy
- Scikit-Learn
- TensorFlow/Keras
- Matplotlib

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/adobe-stock-predictor.git
