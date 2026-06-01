# 📈 Time Series Analysis: Monthly Average Temperatures — Dubuque, IA

**Group 5** | *Submitted: May 8, 2026*

**Dataset:** `tempdub` (TSA package) — January 1964 to December 1975 (144 observations)

---

### Project Overview
This project performs a full time series analysis on historical monthly temperature data for Dubuque, Iowa. The analysis covers data exploration, decomposition, stationarity testing, and forecasting using both **SARIMA** and **Holt-Winters** methods.

### Features
- Additive seasonal decomposition
- Stationarity tests (ADF, KPSS, Ljung-Box)
- SARIMA model selection with `auto.arima()`
- Holt-Winters exponential smoothing
- Model comparison and out-of-sample validation
- 24-month ahead forecasts (1976–1977)

**Tools:** R | `forecast` | `TSA` | `tseries`
