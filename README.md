# Project Title :
Machine Learning-Modelling-Electric-Production-Time-Series-Data-Project.

## Project Overview :
This project focuses on predicting the consumption of electricity in the future using time series analysis. 
The time series data comprises data and consumption percentage columns. 
The goal is to explore trends, seasonality, and other data characteristics to create an efficient predictive model.

## Project Highlights :
- **Dataset Information:** The dataset includes two columns representing the date and consumption percentage.
- **Data Preprocessing:** The initial steps involve importing necessary libraries, loading the dataset, and visualizing the data to gain insights.
- **Time Series Characteristics:** The project explores the time series characteristics, identifying an upward trend and seasonal patterns in the data.
- **Seasonal Decomposition:** Utilizing the multiplicative model, the time series is decomposed into seasonal, trend, and residual components. The stationary seasonal component is used for further analysis.
- **Stationarity Check:** Various methods, including rolling window analysis and the AD-Fuller Test, are employed to check and achieve stationarity in the data.
- **Data Transformation:** Different techniques like differencing and log transformation are applied to make the non-stationary data stationary.
- **AR - AutoRegression:** AutoRegression is employed to model the relationship between an observation and several lagged observations (autoregressive terms).
- **Building ARIMA Models:** Autoregressive Integrated Moving Average (ARIMA) models are constructed to capture the time series patterns, incorporating parameters such as autoregressive order (p), differencing order (d), and moving average order (q).
- **ARIMA and SARIMAX:** The project explores both ARIMA and Seasonal ARIMA (SARIMAX) models, incorporating seasonal components to improve forecasting accuracy.
- **Exponential Smoothing:** Exponential smoothing techniques are applied to provide weighted averages to the observed data, aiding in trend and seasonality identification.
- **Removing Trend:** Further analysis includes removing trend components from the data, allowing for a more accurate understanding of seasonality.
- **Model Evaluation:** The project evaluates the performance of each model using metrics such as Mean Squared Error (MSE)and Mean Absolute Error (MAE).
- **Residual Diagnostic Plots:** Diagnostic plots are analyzed to ensure the quality of the models, including standardized residual plots, histograms, Q-Q plots, and correlogram plots.

## Project Preview :
<img src="Images/SEASONAL DECOMPOSITION (seasonal, trend, residual).png">
<img src="Images/STATIONARITY TESTING - ADFULLER.png">
<img src="Images/ACF and PACF .png">
