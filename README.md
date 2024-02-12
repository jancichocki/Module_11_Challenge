# MercadoLibre Search Trends and Stock Price Analysis

This repository contains an analysis of Google search trends related to MercadoLibre and its correlation with the company's stock price movements. The analysis is performed using Python with libraries such as Pandas, hvPlot, Prophet, and IPython for interactive visualizations and forecasting.

## Overview

The project aims to uncover insights from MercadoLibre's hourly search trends data, analyze the stock price patterns, and forecast future revenue using time series models. This analysis helps understand how search trends correlate with stock performance and predict sales for better financial planning.

## Files

- `google_hourly_search_trends.csv`: Google search trends data for MercadoLibre.
- `mercado_stock_price.csv`: Hourly stock price data for MercadoLibre.
- `mercado_daily_revenue.csv`: Daily sales (revenue) data for MercadoLibre.

## Analysis Steps

1. **Search Trends Visualization**: Visualize Google search trends for MercadoLibre to identify patterns and unusual activity during specific periods.

2. **Seasonality in Search Traffic**: Analyze search traffic data to uncover daily and weekly seasonality.

3. **Correlation Analysis**: Explore the relationship between search trends and MercadoLibre's stock price movements.

4. **Time Series Forecasting with Prophet**:
   - Forecast future search trends using the Prophet model.
   - Analyze components of the forecast to identify when search traffic peaks.

5. **Revenue Forecasting**:
   - Apply the Prophet model to daily sales data to forecast next quarter's revenue.
   - Provide expected, best-case, and worst-case sales scenarios.
