# 🧠 Retail Demand Forecasting using LSTM (Rossmann Dataset)

A PyTorch-based LSTM forecasting pipeline to predict daily sales across different retail stores using the Rossmann dataset.

## 📁 Project Structure

- `retail_demand_forecasting.py` – Main training and evaluation pipeline using PyTorch LSTM
- `requirements.txt` – List of required Python libraries
- `README.md` – Project overview and instructions
- `LICENSE` – MIT License
- `data/` – Folder containing `train.csv`, `test.csv`, and `store.csv`

## 🚀 Features

- Feature engineering: Time-based, cyclical, and store features
- LSTM Model: 3-layer architecture with dropout and batch normalization
- Evaluation: RMSE, MAE, MAPE metrics + visual plots
- Prediction: Future forecasting capability

## 📊 Final Model Performance
The PyTorch LSTM model was successfully trained and evaluated on the Rossmann sales dataset.

- Root Mean Squared Error (RMSE): 2276.86

- Mean Absolute Error (MAE): 1647.48

- Mean Absolute Percentage Error (MAPE): 25.38%

The model was trained on 100,000 filtered rows (stores open and with non-zero sales), using a sequence length of 30 days and 16 time-series and store-level features. The custom LSTM architecture includes three layers with dropout, batch normalization, and fully connected layers.

## 📦 Installation

```bash
pip install -r requirements.txt

