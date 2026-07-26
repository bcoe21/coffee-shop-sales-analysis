# Coffee Shop Sales Analysis

## Overview
Analysis of 149,116 transactions across three NYC coffee shop locations 
to identify key drivers of revenue performance by daypart, product 
category, and store location.

## Tools Used
- **Python** (pandas, matplotlib, seaborn) — data cleaning, 
  feature engineering, and visualization
- **SQL** (SQLite) — querying and aggregating transaction data
- **Tableau Public** — interactive dashboard

## Key Findings
1. **Morning Rush generates 48% of revenue** despite being one 
   of four dayparts — driven entirely by transaction volume 
   not higher spend per customer
2. **Peak hour is 10am, not 8am** — revenue builds gradually 
   through the morning before dropping sharply after 11am
3. **Coffee Beans is the hidden revenue opportunity** — only 
   1,753 transactions but $22.87 average ticket, 5x the store 
   average
4. **All three stores perform within 3% of each other** in 
   total revenue — but Lower Manhattan customers spend more 
   per visit than other locations
5. **Weekdays generate 72% of revenue** — spending behavior 
   is identical on weekends suggesting untapped weekend 
   traffic opportunity

## Project Structure
- `coffee-shop-sales-analysis.ipynb` — full analysis notebook
- `coffee_shop_cleaned.csv` — cleaned dataset used for Tableau

## Dashboard
[View Interactive Dashboard on Tableau Public]([your-tableau-url-here](https://public.tableau.com/app/profile/brenna.coe/viz/CoffeeShopSalesAnalysis_17850996209000/Dashboard1?publish=yes))

## Data Source
Coffee Shop Sales dataset via Kaggle — 149,116 transactions, 
18 variables, June 2023 — March 2024
