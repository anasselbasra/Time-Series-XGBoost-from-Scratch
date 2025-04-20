# PJM Energy Forecasting – Time Series Modeling with XGBoost (from Scratch)

 
> 🧠 Machine Learning project — time series forecasting, model optimization, and real-world energy data

> My participation on [Kaggle](https://www.kaggle.com/code/anasselbasraoui/time-series-xgboost-from-scratch-rmse-282-92)

---

## 📊 Project Overview

This project implements a **machine learning pipeline from scratch** to forecast electricity consumption for the **PJM East** region — a part of PJM Interconnection LLC, a major electricity transmission operator in the United States.

The core objective is to demonstrate how **time series data** can be modeled using **XGBoost**. All components — from data preprocessing to loss minimization — are built and tuned manually.

---

## 🔢 Dataset Description

- **Source**: PJM Interconnection LLC [Kaggle](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption/data?select=AEP_hourly.csv)
- **Type**: Hourly power consumption data (in MW)
- **Region**: PJM East
- **Period**: 2002–2018
- **Granularity**: 1-hour time intervals

Example regions covered by PJM East:
- Pennsylvania
- New Jersey
- Delaware
- Maryland
- Virginia
- District of Columbia

---

## 🧠 Machine Learning Highlights

### 📌 Goal
Predict the next hourly electricity consumption value based on:
- Lagged features
- Time-based features (hour, day of week, etc.)

### ⚙️ What Makes This Project Unique

- **No external AutoML libraries**: All logic is explicitly defined and interpretable
- **Walk-forward validation**: Ensures correct evaluation on temporal sequences

---

## 🔍 Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Comparative error plots over time
- Forecast visualizations (true vs predicted)

---

## 🛠️ Tech Stack

- Python (3.8+)
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebooks

---

## ✍️ Author

**Anass El Basraoui**  
Final-year student in Statistics & Data Science (ENSAI)  
Focus: Applied machine learning, interpretable modeling, and energy systems forecasting
