# R-project-1
This repository contains two mini-projects written in R that analyze **yearly stock returns** for selected companies in the **automotive** and **technology** sectors from **2020 to 2024**. Both projects use financial time series data retrieved via the `quantmod` package and visualized with `PerformanceAnalytics`.

# Stock Return Analysis Using R (2020–2024)
This repository contains two R mini-projects analyzing the **yearly returns of selected stocks** in the **automotive** and **technology** sectors between 2020 and 2024. The projects use `quantmod` and `PerformanceAnalytics` packages to download, compute, and visualize financial time series data.

## Project 1: Automotive Sector

**Stocks Analyzed:**
- Tesla (TSLA)
- BMW (BMW.DE)
- Audi (VOW3.DE)

**Main Steps:**
- Load adjusted closing prices using `getSymbols()`
- Extract end-of-year prices
- Calculate yearly discrete returns
- Visualize returns with `chart.TimeSeries()`

---

## Project 2: Technology Sector

**Stocks Analyzed:**
- Apple (AAPL)
- Microsoft (MSFT)
- Meta (META)
- Google (GOOG)
- Adobe (ADBE)

**Main Steps:**
- Load adjusted prices from Yahoo Finance
- Get last trading day of each year
- Compute yearly discrete returns
- Visualize results using time series charts

---

## Tools & Packages Used

```r
quantmod               # Download stock data and manage time series
PerformanceAnalytics   # Calculate returns and plot performance charts
