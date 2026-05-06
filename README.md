# Value Investing Dashboard

## Overview
Built a Power BI dashboard to analyze market price versus intrinsic value across selected equities using API-driven financial data. The project implements a lightweight ETL workflow within Power BI, including data extraction, transformation, modeling, and visualization.

## Features
- KPI cards for valuation insights
- Scatter plot comparing price vs intrinsic value
- Discount % ranking analysis
- Price vs intrinsic value comparison
- Detailed valuation table

## Tech Stack
- Power BI
- Power Query
- DAX

## Data Sources
- Financial Modeling Prep API
- Yahoo Finance

## Key Insight
All selected equities are currently trading above intrinsic value, with TSLA showing the largest valuation gap.

## Challenges & Limitations
- Financial data APIs required paid access tiers for expanded functionality and reliable usage limits.
- Power BI visualization constraints made implementing a dynamic fair value reference line difficult within the native scatter chart visual.
- Intrinsic value calculations are simplified estimates and may differ from professional valuation models.
- Future enhancements could include custom visuals, Python integration, or advanced DCF modeling.

## Dashboard Preview
![Dashboard](Value%20Investing%20Dashboard.jpeg)

## Disclaimer
This project is for educational and portfolio purposes only and should not be considered financial or investment advice. Always conduct your own research and invest at your own discretion.
