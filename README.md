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

## 📦 Installation

```bash
pip install -r requirements.txt

