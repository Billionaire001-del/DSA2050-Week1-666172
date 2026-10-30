# DSA 2050 Week 2 Practical — Retail Sales Analysis

**Name:** Dancan Ratemo Mayaka  
**Student ID:** 666172

## Project objective
Summarize retail sales performance to help a retail manager decide which product category merits promotional consideration. This is primarily descriptive analysis: it summarizes observed sales, not causal effects or a forecast.

## Unit of analysis
One row represents a sale/order line. `OrderID` is unique in this dataset, so each row also corresponds to one recorded order.

## KPIs
1. Total revenue (KES): KES 3,206,450
2. Number of recorded orders: 300
3. Average revenue per recorded order: KES 10,688.17

## Initial findings
- The dataset records KES 3,206,450 revenue across 300 orders, averaging KES 10,688.17 per order.
- Electronics has the highest category revenue at KES 934,500; Personal Care follows closely at KES 931,800.

## Limitation
The dataset covers January–March 2026 and omits costs/margins, stock availability, discounts, customer demographics, and causal evidence. Revenue cannot establish profitability or prove that a promotion would increase sales.

## Reproduce
From the repository root, install dependencies with `pip install -r requirements.txt`, then launch `jupyter notebook week1_analysis.ipynb` and run all cells. The notebook loads `retail.csv` using a relative path.
