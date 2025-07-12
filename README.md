# Predictive Analytics for Stock Market Trends Using Machine Learning

This project aims to predict stock market trends using historical price data and machine learning models, including Linear Regression and LSTM (Long Short-Term Memory) neural networks.

## 📊 Dataset
- Source: Yahoo Finance via `yfinance` Python package
- Example stock used: `RELIANCE.NS` (Reliance Industries)

## 🧠 Models Used
- Linear Regression (baseline)
- LSTM (for time-series forecasting)

## 📁 Files Included
- `stock_prediction.ipynb`: Jupyter Notebook with complete implementation
- `README.md`: Project overview and instructions

## 📈 Output
The notebook includes:
- Data visualization of historical prices
- LSTM-based future price prediction
- Graphical comparison of actual vs predicted prices

## 🚀 How to Run
1. Open `stock_prediction.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
2. Install dependencies using:
   ```bash
   pip install yfinance tensorflow scikit-learn matplotlib pandas
