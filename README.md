# 📈 Walmart Sales Forecasting Using ARIMA

This project predicts future weekly sales for a Walmart store using historical data and time series forecasting (ARIMA model).

## 📊 Dataset

- Source: Walmart Sales Dataset
- Rows: 6,435
- Columns: Store, Date, Weekly_Sales, Holiday_Flag, etc.

## 🎯 Objective

Build a model to forecast future weekly sales of **Store 1** based on past trends.

## 🔧 Tools Used

- Python (pandas, matplotlib, pmdarima, statsmodels)
- Jupyter Notebook
- ARIMA Model for Time Series Forecasting

## 🧠 Process

1. Loaded and cleaned the data
2. Focused on Store 1 sales
3. Visualized trends over time
4. Checked stationarity (ADF test)
5. Used Auto ARIMA to find best model → ARIMA(2,1,3)
6. Forecasted next 12 weeks
7. Evaluated model using MAE and RMSE

## 📈 Results

- **MAE**: 104,878.25  
- **RMSE**: 122,601.63  
- 12-week forecast was visualized with confidence intervals

## 🖼️ Forecast Plot

![Forecast](images/forecast_plot.png)

## 📁 Folder Structure

