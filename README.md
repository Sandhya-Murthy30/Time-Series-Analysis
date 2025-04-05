# Time-Series-Analysis


# 📈 Time Series Analysis Dashboard using R Shiny

This project is an interactive and modular **R Shiny dashboard** designed for comprehensive time series analysis. It supports data upload, preprocessing, decomposition, stationarity testing, modeling (ARIMA, SARIMA, GARCH, etc.), residual diagnostics, forecasting, and report generation.

---

## 🚀 Features

✅ Upload Excel files and select time series column  
✅ View data and inspect column information  
✅ Create and visualize time series plots  
✅ Apply transformations (log, differencing, moving average, etc.)  
✅ Decompose time series (Additive or Multiplicative)  
✅ Perform ADF Stationarity Tests  
✅ Model using AR, MA, ARMA, ARIMA, SARIMA, ARCH, and GARCH  
✅ Diagnostic plots: Residuals, ACF/PACF, QQ plots  
✅ Forecasting: Exponential Smoothing, Holt-Winters, ARIMA  
✅ Generate final reports and download summary

## 📂 File Structure

install.packages(c("shiny", "shinydashboard", "tseries", "ggplot2", "forecast", 
                   "TTR", "lmtest", "readxl", "rugarch", "urca"))
