# Stock Market Time Series Analysis and Forecasting

## Project Overview

This project aims to analyze and forecast stock market trends using advanced time series analysis techniques. The goal is to explore historical data, detect patterns, and make accurate short-term and long-term predictions. By leveraging real-world financial data, we develop models to interpret and forecast stock prices, providing insights into investment planning and risk management.

### Internship Details

* **Role:** Data Analyst Intern
* **Organization:** Zidio Development
* **Duration:** 15 May 2025 – 15 June 2025
* **GitHub Repository:** [Stock Analysis ZD](https://github.com/yashraj195/Stock_Analysis_ZD)

### Team Members & Responsibilities

* **Aaditya Mehta:** Data Collection & Description
* **Team Member 2:** Data Cleaning & Preprocessing
* **M. Fathimuthujohara:** Exploratory Data Analysis & Model Evaluation
* **Yash Raj:** Feature Engineering
* **Bhuvana Sandhya Rani Samuji:** Time Series Modeling
* **Prithikasree S B:** Final Documentation & Presentation

## Project Objectives

1. Collect and preprocess historical stock market data.
2. Analyze time series concepts such as trend, seasonality, noise, and stationarity.
3. Implement and compare models like ARIMA, SARIMA, Prophet, and LSTM for forecasting.
4. Visualize trends, volatility patterns, and model predictions.
5. Evaluate model accuracy using standard metrics.
6. Deploy a forecasting pipeline for practical financial insights.

## Data Description

* **Source:** Microsoft Stock Data from Kaggle
* **Format:** CSV
* **Features:**

  * Date: Trading day
  * Open: Opening price
  * High: Highest price of the day
  * Low: Lowest price of the day
  * Close: Closing price
  * Volume: Number of shares traded
* **Date Range:** 2015-04-01 to 2021-03-31
* **Tools:** Pandas, NumPy, Scikit-learn, Keras

## Methodology

### 1. Data Preprocessing

* **Missing Values:** Filled using forward-fill methods.
* **Outlier Detection:** Z-score and IQR to handle anomalies.
* **Datetime Conversion:** Converted 'Date' to datetime format.
* **Feature Scaling:** Applied Min-Max scaling for consistency.
* **Train-Test Split:** Chronological split (80% train, 20% test) to prevent data leakage.

### 2. Exploratory Data Analysis (EDA)

* **Price Trends:** Visualized daily fluctuations using line plots.
* **Volume Analysis:** Identified periods of high trading activity.
* **Correlation Analysis:** Examined relationships between Open, High, Low, Close, and Volume.
* **Rolling Averages:** Plotted 7-day and 30-day moving averages to analyze trends.
* **Volatility Analysis:** Examined standard deviations of returns.

### 3. Feature Engineering

* **Time-Based Features:** Extracted year, month, day, and weekday from the date.
* **Price Movement Features:**

  * Price Range = High - Low
  * Percent Change = (Close - Previous Close) / Previous Close
* **Technical Indicators:**

  * Moving Averages (5, 10, 20 days)
  * Volatility Indicators (10-day standard deviation)
  * Momentum Indicators (5-day difference)
  * Volume Change: Percent change in daily volume

### 4. Time Series Modeling - LSTM

* **Model Structure:**

  * LSTM Layer with 50 units
  * Dropout Layer (0.2) for regularization
  * Dense Output Layer (1 neuron)
* **Training Configuration:**

  * Loss Function: Mean Squared Error
  * Optimizer: Adam
  * Epochs: 50
  * Batch Size: 32
* **Performance:**

  * RMSE: 3.26
  * MAE: 2.85
  * MAPE: 1.79%

### 5. Model Evaluation

* **Forecast Accuracy:** Predicted values closely followed actual prices.
* **Error Analysis:** Slight deviations observed during sudden trend reversals.
* **Generalization:** Model maintained stability in long-horizon predictions.

## Future Enhancements

* Incorporate external data such as news sentiment and economic indicators.
* Experiment with hybrid models (e.g., CNN-LSTM) to capture spatial and temporal features.
* Implement a dashboard for real-time prediction visualization.

## References

* Jason Brownlee – Time Series Forecasting with Python
* François Chollet – Deep Learning with Python
* Microsoft Stock Dataset – Yahoo Finance
* Scikit-learn Documentation
* Keras LSTM Tutorial

For complete code and visualizations, visit the [GitHub Repository](https://github.com/yashraj195/Stock_Analysis_ZD).
