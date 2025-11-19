# Business-Dashboard-Project
An interactive Power BI dashboard visualizing sales, profit, and region‑wise performance to empower stakeholders with data‑driven insights. It tracks key metrics and growth trends, helping businesses identify opportunities quickly.
## Overview
This project contains an *interactive business dashboard* created using *Power BI*.  
The dashboard is designed to help business stakeholders monitor key performance indicators (KPIs) such as *Sales, Profit, Growth, and Region-wise performance*.  

The goal is to provide insights for informed decision-making.

---

## Features
- *Interactive Dashboard* with filters and slicers
- *KPI Cards*: Total Sales, Total Profit, Profit Margin, Customer Count
- *Charts & Visuals*:
  - Sales trends (line chart)
  - Region-wise sales (map or bar chart)
  - Product-wise sales (bar/column chart)
  - Profit analysis (column chart, card)
- *Time-series Analysis* for Year-over-Year growth
- *Navigation Menu* with buttons to switch between pages
- *Consistent Theme*: 2–3 color palette with professional fonts

## DAX
Total_Sales = SUM(sales_data[Revenue])
Total_Profit = SUM(sales_data[Profit])
Profit_Margin = DIVIDE([Total_Profit], [Total_Sales])
Customer_Count = DISTINCTCOUNT(sales_data[CustomerID])
YoY_Growth = ([Total_Sales] - CALCULATE([Total_Sales]))

## Steps in creating this project

Open Power BI Desktop.

Load the provided dataset.

Open the PBIX file included in the repository.

Use filters/slicers to explore different regions, products, or time periods.

Click the navigation buttons to switch between dashboard pages.

## Tools Used

Power BI Desktop (Free version)

Kaggle Dataset (Free to download)

## Outcome

This project demonstrates the creation of a professional interactive dashboard that can:

Help track business performance

Identify trends in sales and profit

Support data-driven decision-making
