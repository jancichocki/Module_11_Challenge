# MercadoLibre Search Trends and Stock Analysis

## Project Overview

This project aims to analyze MercadoLibre's Google search trends, correlate these trends with the company's stock price movements, and forecast future user search traffic and revenue using time series models. By leveraging data visualization and predictive modeling, this project provides insights into the temporal patterns of user interest and their potential impact on financial performance.

## Objectives

- Visualize Google Search traffic seasonality and identify unusual patterns.
- Evaluate the correlation between MercadoLibre's stock price and Google Search traffic.
- Forecast hourly user search traffic using the Prophet model.
- Analyze and predict the company’s future revenue (optional).

## Dataset

The analysis utilizes three primary data sources:

- `google_hourly_search_trends.csv`: Hourly Google Search trends data for MercadoLibre.
- `mercado_stock_price.csv`: Hourly stock price data for MercadoLibre.
- `mercado_daily_revenue.csv`: Daily revenue figures for MercadoLibre.

## Analysis Workflow

### 1. Search Traffic Analysis

- **Objective**: Identify unusual search traffic patterns and their correlation to financial events.
- **Method**: Visualization of May 2020 search data using `hvPlot` and comparison of traffic to the monthly median.

### 2. Seasonality in Search Traffic

- **Objective**: Uncover predictable seasonal patterns in search data.
- **Method**: Analysis of traffic by day of the week and week of the year, visualized as heatmaps.

### 3. Correlation with Stock Prices

- **Objective**: Determine if a relationship exists between search trends and stock prices.
- **Method**: Integration of search and stock price data, followed by a correlation analysis.

### 4. Time Series Forecasting

- **Objective**: Forecast future search traffic.
- **Method**: Application of the Prophet forecasting model to search data.

### 5. Revenue Forecasting (Optional)

- **Objective**: Predict total sales for the next quarter.
- **Method**: Use of the Prophet model on daily sales data to identify seasonal patterns and forecast revenue.

## Key Findings

- The analysis revealed significant seasonality in search traffic, correlating with specific days of the week and times of the year.
- A correlation study suggested a relationship between search trends and stock price movements, particularly in response to market events.
- The Prophet model forecasts indicated both the potential for increased search popularity and revenue in the near term, with identifiable patterns in daily and weekly traffic.
