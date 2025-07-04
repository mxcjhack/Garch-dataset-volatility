# Volatility Prediction using GARCH Model

Overview
This project implements volatility forecasting for Indian equity indices using the Generalized Autoregressive Conditional Heteroskedasticity (GARCH) model. The focus is on the NIFTY 50, NIFTY MIDCAP 150, and NIFTY SMALLCAP 250 indices, utilizing historical data from 2004 to 2024. The goal is to provide actionable insights for risk management, portfolio optimization, and option pricing by accurately modeling and predicting market volatility.

## Features
### Indices Covered:
- NIFTY 50 (2004–2024)
- NIFTY MIDCAP 150 (2010–2024)
- NIFTY SMALLCAP 250 (2010–2024)

### Modeling:
- GARCH(2,2) and related variants for volatility estimation
- Rolling-window and out-of-sample forecasting
- Statistical testing (PACF, stationarity)

### Evaluation:
- Mean Squared Error (MSE), Log-Likelihood
- Visual comparison of predicted vs. actual volatility

## Usage
### Data Preprocessing:
Load and clean historical OHLC data, convert to daily returns, and ensure stationarity.

### Model Selection:
Use PACF plots to determine appropriate GARCH order.

### Model Fitting:
Fit GARCH models to returns data for each index.

### Forecasting:
Perform rolling-window and 7-day ahead volatility forecasts.

### Evaluation:
Assess predictions with MSE, log-likelihood, and visual plots.

## Results
- GARCH(2,2) models successfully captured volatility clustering in Indian equity indices.

- Rolling forecasts demonstrated adaptability to dynamic market conditions.

- The approach is practical for financial risk management and investment strategy.

Authors
Suvendu Panda
Monalisa Pal
Prasoon Modi
Tejas Binu
Harmanjot Singh

Mentor: Dr. Mainak Bandyopadhyay
School of Computer Science and Engineering, KIIT Deemed to be University
