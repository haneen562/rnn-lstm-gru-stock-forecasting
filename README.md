# 📈 Time Series Stock Forecasting — RNN vs LSTM vs GRU

A deep learning project that compares three recurrent neural network architectures for predicting Apple Inc. (AAPL) stock prices.

## 🎯 Overview

This notebook benchmarks **Simple RNN**, **LSTM**, and **GRU** models on the same stock price dataset using identical architecture depth to ensure a fair comparison.

## 🧠 Models

| Model | Description |
|-------|-------------|
| 🔵 Simple RNN | Baseline recurrent model |
| 🟢 LSTM | Long Short-Term Memory — handles long-term dependencies |
| 🟠 GRU | Gated Recurrent Unit — efficient alternative to LSTM |

## 📊 Dataset

- **Stock:** Apple Inc. (AAPL)
- **Source:** `yfinance`
- **Period:** 2018–2023
- **Feature used:** Daily closing price

## 🔧 Methodology

1. Download 5 years of AAPL closing prices
2. Normalize data with MinMaxScaler
3. Create 60-day sliding window sequences
4. 80/20 train-test split
5. Train all three models with EarlyStopping
6. Compare using RMSE, MAE, and R² Score

## 📦 Requirements

```bash
pip install tensorflow yfinance scikit-learn matplotlib pandas numpy
```

## 🚀 Run

Open the notebook in Jupyter or Google Colab and run all cells sequentially.

## 📈 Evaluation Metrics

- **RMSE** — Root Mean Squared Error
- **MAE** — Mean Absolute Error
- **R² Score** — Coefficient of Determination

## 👩‍💻 Author

**Haneen Nasser**
