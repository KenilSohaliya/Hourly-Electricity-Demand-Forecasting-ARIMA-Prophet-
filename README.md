# Hourly Electricity Demand Forecasting (ARIMA + Prophet)

Time series forecasting project on **hourly electricity consumption** (PJME grid).  
Goal: detect long-term trends and seasonality, then forecast demand with clear uncertainty estimates.

## Key Results
- Built forecasting models using **ARIMA** and **Prophet**
- Achieved approximately **~6% MAPE**
- Visualized forecasts with **confidence intervals**
- Shared optimization insights to support energy planning and reduce peak-demand risk

## Methods Used
- Time series cleaning and resampling (hourly)
- Trend + seasonality analysis
- Train/validation split for time series
- Model comparison (ARIMA vs Prophet)
- Error metrics: MAPE (and optional MAE/RMSE)

## Tech Stack
- **Python**
- Pandas, NumPy
- Statsmodels (ARIMA), Prophet
- Plotly / Matplotlib (visualizations)

## How to Run
1. Clone the repo  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
