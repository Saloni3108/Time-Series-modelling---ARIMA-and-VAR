# Time-Series-modelling---ARIMA-and-VAR
This repository contains the Univariate(ARIMA) and Multivariate(VAR) time series modelling.

Problem Statement - To forecast 'Iron Ore price index'

1. ARIMA - Univariate Time Series Forecasting 
(https://github.com/Saloni3108/Time-Series-modelling---ARIMA-and-VAR/blob/main/ARIMA.ipynb)

ARIMA stands for Auto regressive Integrated Moving Averages. Before modelling, it is important to carry out 

a) check for stationary, seasonality , trends.

b) Check the order of differencing (if non-stationary)

c) ACF and PACF  for determination of autoreressive order (p) and moving averages order(q)

d) Auto-arima model - Kind of GridSearch, which comes up with the optimal combination of p,d,q, such that AIC is lowest

e) Forecast the time-series values 


2. VAR - Multivariate Time Series Forecasting  
(https://github.com/Saloni3108/Time-Series-modelling---ARIMA-and-VAR/blob/main/VAR.ipynb)

This method takes into consideration other variables , while forecasting targetted variable. In doing so, we perform Granger Causality test to understand if other variables and 
their lagges values have some consideration in target variable. The variables with p value > significance level (10% here), are assumed to have no cause and effect relation with the targetted variable.

a) Check for stationary

b) Granger's Causality test - Understand the cause effect of other variables on targetted variable

c) Cointegration test - To establish significance between variables

d) Foreacsting

e) Performace evaluation based on rmse and mape.

