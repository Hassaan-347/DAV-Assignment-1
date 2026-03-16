# FORTIS Stock Price Analysis and Forecasting using ARIMA

## Project Overview
This project analyzes historical stock price data of **FORTIS** and applies the **ARIMA time series model** to forecast future closing prices. The work was completed as part of a university assignment in **Data Analytics**.

The objectives of this project were to:
- preprocess stock market data,
- visualize the historical closing price trend,
- test for stationarity using the ADF test,
- analyze ACF and PACF plots,
- build an ARIMA model,
- forecast the next 30 days of closing prices,
- interpret the forecasting results.

---

## Dataset
- `data/Quote-Equity-FORTIS-EQ-13-03-2025-13-03-2026.csv`
- **Stock:** FORTIS
- **Source Format:** CSV
- **Date Range:** 13-Mar-2025 to 13-Mar-2026

## Graphs
![Overview](Graph1.png)
![ACF Plot](ACF.png)
![PACF Plot](PACF.png)
![ARIMA Reading](ARIMAGraph.png)
![Prediction](Forecast.png)

## Summary of Findings and Observations

The historical analysis of FORTIS stock data shows noticeable fluctuations in the closing price over the observed time period. The stock experienced an upward trend during the middle portion of the dataset, followed by a decline and increased volatility in the later months. 

The Augmented Dickey-Fuller (ADF) test indicated that the original time series was non-stationary, which required differencing before applying the ARIMA model. After differencing, the series became more stable, allowing the ARIMA model to be fitted appropriately.

Based on the ARIMA model forecasting results, the predicted closing prices for the next 30 trading days remain relatively stable around the most recent observed price levels. This suggests that the model does not indicate a strong upward or downward trend in the immediate future. However, since stock prices are influenced by many external factors such as market conditions, company performance, and economic events, the forecast should be interpreted as a statistical estimate rather than a guaranteed prediction.
