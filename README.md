# Traffic Prediction Using Time Series Models

This repository contains a Jupyter Notebook implementing and analyzing time series models for traffic prediction. The project utilizes **Prophet**, **SARIMA**, and **SARIMAX** to forecast traffic patterns based on historical data. This project was performed as a part of course - STAT 7110: Forecasting Methods for Management

---

## Project Overview

Time series forecasting is crucial for understanding and managing traffic flow, enabling better decision-making for transportation systems. In this project, we:

1. Explored and preprocessed traffic data to prepare it for modeling.
2. Built and compared three popular time series models:
   - **Prophet**: A model developed by Facebook for automatic forecasting.
   - **SARIMA (Seasonal ARIMA)**: A well-known statistical model handling seasonality.
   - **SARIMAX**: An extension of SARIMA incorporating external regressors.

---

## Key Steps

1. **Data Preprocessing**:
   - Handled missing values and irregular time intervals.
   - Visualized traffic trends, seasonality, and noise.

2. **Model Building**:
   - Configured and optimized parameters for Prophet, SARIMA, and SARIMAX.
   - Conducted model training using historical traffic data.

3. **Evaluation and Analysis**:
   - Used metrics like RMSE (Root Mean Square Error) and MAE (Mean Absolute Error) to evaluate model performance.
   - Visualized predictions and compared actual vs. forecasted traffic.

---

## Results & Insights

- **Prophet**:
  - Strengths: Automatically detects seasonality and handles missing data well.
  - Limitations: Slightly less accurate for very short-term predictions.

- **SARIMA**:
  - Strengths: Provides good predictions when seasonality and trends are well-defined.
  - Limitations: Requires parameter tuning and may struggle with complex external influences.

- **SARIMAX**:
  - Strengths: Accounts for external variables affecting traffic, providing more robust predictions in certain scenarios.
  - Limitations: Complexity increases with the addition of external variables.

- **Overall Insights**:
  - SARIMAX generally performed better when external regressors were significant.
  - Prophet was ideal for ease of use and long-term forecasting.
  - SARIMA excelled in scenarios with consistent seasonal patterns.

---
