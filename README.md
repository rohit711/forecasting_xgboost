# forecasting_xgboost
The goal of this project is to show how to transform a time series dataset into a supervised learning format using lag features


# 📈 XGBoost Time Series Forecasting Demo

This project demonstrates how to apply **XGBoost**, a popular gradient boosting algorithm, to a **univariate time series forecasting** problem using **lag-based feature engineering**. Unlike classical models like ARIMA or Prophet, XGBoost does not assume linearity or stationarity — making it a powerful alternative for capturing complex patterns.

---

## 🔍 Purpose

The goal of this project is to:

- Show how to **convert time series data into a supervised learning format** using lag features
- Train and evaluate an **XGBoost regressor** to forecast future values
- Visualize predictions with **Plotly**, including a vertical line that separates the training vs. forecast period
- Demonstrate how **machine learning models can outperform traditional models** with the right feature engineering
- Provide a **reusable forecasting pipeline** for future time series ML projects

---

## 📂 Dataset

The dataset used is:
> **Daily Minimum Temperatures in Melbourne, Australia**  
Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Daily+Minimum+Temperatures+in+Melbourne)

- Column: `Temp` — Minimum temperature (in °C)
- Date Range: 1981–1990 (10 years of daily records)

---

## ⚙️ Project Structure

```bash
xgboost-forecast-demo/
├── data/
│   └── daily-min-temperatures.csv
├── forecast_xgboost.py
├── forecast_plot.png
├── forecast_video.mp4
├── requirements.txt
└── README.md
