# Olist SQL Analysis

## Project Overview
This project analyzes Olist e-commerce data using SQL to understand which product categories drive revenue and whether top-performing categories are driven more by higher prices or sales volume.

## Business Question
What product categories drive revenue, and are top categories driven by premium pricing or by higher sales volume?

## Dataset
- Olist order items
- Olist products
- Product category name translation

## Tools Used
- SQL
- SQLite

## Files
- `queries.sql` — SQL queries for revenue by category, average price by category, and quantity sold by category

## Key Findings
- Top revenue categories did not fully overlap with the highest average-price categories.
- This suggests that some leading categories are driven more by volume than by premium pricing.
- Lower-ticket categories appear to contribute strongly to revenue through higher quantity sold.

## Next Step
Analyze seasonality, pricing, and promotions by category to determine whether demand patterns differ between higher-ticket and lower-ticket categories.