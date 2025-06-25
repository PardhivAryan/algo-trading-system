# Algo-Trading System with ML & Google Sheets Automation

## 📌 Objective
This project implements a basic algo-trading strategy using:
- RSI and Moving Average crossover
- ML prediction using Decision Tree
- Google Sheets logging

## Features
- Fetches stock data using Yahoo Finance
- Implements a buy/sell strategy (RSI < 30, 20-DMA > 50-DMA)
- Predicts next-day direction using RSI, MACD, Volume
- Logs trades to Google Sheets with summary
- Modular and well-logged code

## Technologies Used
- Python (pandas, NumPy, yfinance, scikit-learn)
- Google Sheets API
- Google Service Account JSON
- Jupyter Notebook

## ML Component
- Decision Tree Classifier
- Features: RSI, MACD, Volume
- Target: Next-day price direction

## Files
- `algo_trading_system.ipynb` – main notebook
- `credentials.json` – service account for Google Sheets
- `README.md` – project overview

## Video Demo
- [Strategy and Code Flow](your_google_drive_or_youtube_link_1)
- [Console and Google Sheets Output](your_google_drive_or_youtube_link_2)




