# 📈 Stock Price Trend Prediction using LSTM

Predict future stock prices using historical data and deep learning (LSTM).  
This project focuses on **Apple Inc. (AAPL)** stock from 2018–2023, integrating technical indicators like **Moving Averages** and **RSI**.

---

## 🚀 Project Highlights

- 📊 **Data Source**: Yahoo Finance via `yfinance`
- ⚙️ **Model**: Long Short-Term Memory (LSTM) Neural Network (TensorFlow/Keras)
- 🧠 **Input**: 60 previous closing prices
- 🎯 **Output**: Next-day predicted price
- 📉 Includes Moving Averages (50-day, 200-day) and RSI Indicator
- 💾 Model saved as `.h5` for future use or deployment

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `stock_price_prediction_lstm.ipynb` | Full Jupyter Notebook with data prep, LSTM training, graphs |
| `stock_price_lstm_model.h5` | Trained LSTM model |
| `Project_Report.pdf` | Final report with abstract, tools, steps, and results |
| `README.md` | Project documentation |

---

## 🧪 Libraries Used

- `pandas`, `numpy` for data manipulation
- `matplotlib` for plotting
- `scikit-learn` for normalization
- `yfinance` for stock data
- `tensorflow.keras` for LSTM model

---

## 📈 Key Graphs

- Actual vs Predicted Price (single & multiple days)
- Moving Averages (MA50, MA200)
- Relative Strength Index (RSI)

---

## 🧠 Model Architecture

- **Input**: 60-day closing price window
- 2 stacked `LSTM` layers
- `Dropout` for regularization
- `Dense` layer for prediction
- Optimizer: `adam`
- Loss function: `mean_squared_error`

---

## 🔧 How to Run the Project

1. Clone this repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/stock-price-prediction-lstm.git
   cd stock-price-prediction-lstm
