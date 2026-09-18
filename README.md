# Superstore Sales Analysis

## Project Description

Analysis of retail sales data to identify profit drivers and underperforming regions.

## Dataset Source

[Kaggle - Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

## Questions Answered

1. Which categories and sub-categories generate the highest sales and profit?
2. Which regions/states show the highest losses?
3. What is the relationship between discount and profitability?
4. How do sales trend over time (monthly/seasonal)?
5. Who are the top customers by value (sales/profit)?
6. Which shipping mode is the most costly?

## Tools Used

Python, Pandas, Matplotlib, Seaborn

## Key Findings

- **Category profitability varies significantly:** Furniture has a much lower profit margin (2.5%) than Office Supplies and Technology (~17% each), driven by losses in the Tables and Bookcases sub-categories.
- **Losses are geographically concentrated:** Texas has the largest absolute loss (-$25,729), while Ohio has the worst relative performance (-21.7% margin) — almost entirely due to one city, Lancaster (-87.2% margin).
- **High discounts often hurt profitability, but not always:** Tables and Bookcases show negative profit alongside high discounts (26% and 21%), but Binders remains profitable despite the highest discount (37%), showing the effect depends on baseline margin.
- **Sales show consistent growth and seasonality:** Monthly sales roughly doubled from 2014 to 2017, with a recurring dip in January and peak around November/December (holiday season).
- **Top customers are mostly profitable, with one exception:** 9 of the top 10 customers by sales are profitable, but the highest-spending customer (Sean Miller) is actually unprofitable.
- **Shipping mode has minimal profitability impact:** The difference between the best and worst shipping modes is only about $4.35 in average profit per order.