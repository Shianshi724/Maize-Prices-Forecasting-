# Maize-Prices-Forecasting-
This project forecasts wholesale maize prices (₹/quintal) for two markets in Udaipur using Excel-based time series techniques. The goal is to understand future price movements in order to plan marketing decisions more effectively. 
The workbook contains annual maize price series for:
- Grain Market (Prices) – Yearly prices and forecasts up to 2031. [Sheet 1]
- Fatehnagar Market (Prices) – Yearly prices and forecasts up to 2031. [Sheet 2]  

## Methodology
The analysis uses univariate time series techniques implemented directly in Excel: 
- **Time series smoothing** with a 3‑period moving average to highlight underlying price trends before forecasting. 
- **ETS (Exponential Smoothing) forecasting** via Excel’s ETS/FORECAST.ETS‑type approach to capture level and trend in maize prices. 
- **Uncertainty quantification** through lower and upper confidence bounds for each forecasted year to represent forecast risk. 
- **Error analysis** using the Error_ETS column to assess how close ETS forecasts are to actual prices in the historical period. 

## Key Outputs
- Forecasted maize prices for Grain Market and Fatehnagar Market up to 2031. 
- Smoothed series using moving averages for better visualization of long‑run price trends. 
- Approximate forecast accuracy indicators based on ETS forecast errors.

## Skills and Tools
- **Tools:** Microsoft Excel (formulas, time series functions, basic data cleaning and formatting). 
- **Techniques:** Time series smoothing, moving averages, ETS/exponential smoothing forecasting, confidence intervals, forecast error evaluation. 
- **Domain:** Agricultural economics, price analysis for maize markets in India. 
