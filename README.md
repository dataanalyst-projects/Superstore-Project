# Superstore Sales & Profit Dashboard

An interactive Power BI dashboard analyzing sales, profit, and shipment trends for a retail superstore.

![Dashboard Preview](SuperstoreDashboard.png)


## Problem
Retail stakeholders needed a single view to track sales and profit performance across regions, categories, and customer segments — and to spot trends over time and by shipment mode.

## Data
- `superstore_cleaned.csv` — 8,123 order line items, 22 fields
- Key fields: Order Date, Ship Date, Ship Mode, Customer, Segment, Region, State, City, Category, Sub-Category, Sales, Quantity, Discount, Profit
- Cleaned in Python: standardized date fields, verified numeric types for Sales/Profit/Discount

## Tools
Python · Power BI · Power Query · DAX

## What I Built
- **3 KPI cards:**
-  Total Profit (443K), Quantity Sold (31K), Total Sales (2M)
-  
- **Pie charts:**
-  Profit by Region, Quantity by Segment
-  
- **Line chart:**
-  Profit by Year (2014–2017), showing consistent year-over-year growth
-  
- **Area chart:**
-  Sales by Order Date, tracking daily sales volatility
-  
- **Bar chart:**
-  Sales by Category (Technology, Office Supplies, Furniture)
-  
- **Filters:**
-  State and City slicers, Shipment Mode selector (First Class, Second Class, Same Day, Standard Class)

## Result
A fully interactive dashboard letting stakeholders drill from company-wide totals down to a single state, city, or shipment mode — surfacing insights like West and South regions driving over half of total profit, and Technology outselling Office Supplies and Furniture.
