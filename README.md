# Commodities & Currency Market Insights – Power BI Dashboard

![Dashboard](dashboard.png)

## Overview
An interactive Power BI dashboard built from Excel source data to analyze long-term price trends of Brent oil, gold and silver, and the structure of global payment currencies and offshore RMB markets.

University group project (M.Sc. Data Science, University of Europe for Applied Sciences) – 5 members. **My role: Team Lead.**

## Tools
Power BI · Excel

## Data Preparation
- Combined multiple Excel datasets on commodity prices and currency markets
- Cleaned and standardized inconsistent date formats to enable multi-decade trend analysis

## Dashboard Visuals
| Visual | What it shows |
|---|---|
| Brent Oil Price Trend | Long-term Brent oil price development |
| Gold Price Long-Term Trend | Gold price over several decades |
| Silver Price Trend and Peaks | Silver price development and major peaks |
| Commodity Volatility Comparison | Relative volatility of gold, silver and Brent oil (coefficient of variation) |
| Top 5 Global Payment Currencies | Share of USD, EUR, GBP, JPY and CNY in global payments |
| Top Offshore RMB Economies | Economies with the largest share of offshore RMB activity |

## Key Insights
- **USD** accounts for about **60%** of payments among the top 5 currencies, followed by **EUR** at about **24%**.
- Over the full period, **gold and silver** show much higher relative variability (coefficient of variation ≈ 1.6) than **Brent oil** (≈ 0.6).
- **Hong Kong** holds by far the largest share of offshore RMB activity.

## Files
- `dashboard.png` – dashboard screenshot
- `*.pbix` – Power BI report file
- `data/` – source datasets
