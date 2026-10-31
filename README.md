# Week 1 – Power BI Sales Dashboard

## Project Overview
This project is developed as part of my Week 1 assignment to understand Power BI fundamentals, data cleaning, data modelling, DAX calculations, and dashboard creation.

## Tools Used
- Microsoft Power BI Desktop
- Microsoft Excel
- Power Query
- DAX

## Dataset
The dataset contains sales information including:
- Order ID
- Order Date
- Region
- Product
- Category
- Quantity
- Price
- Cost per Unit

## Data Preparation
- Imported Excel data into Power BI.
- Handled missing values.
- Changed column data types.
- Created calculated columns.

## DAX Calculations

**Revenue**
```dax
Revenue = SalesData[Qty] * SalesData[Price]
```

**Profit**
```dax
Profit = SalesData[Qty] * (SalesData[Price] - SalesData[CostPerUnit])
```

**Total Revenue**
```dax
Total Revenue = SUM(SalesData[Revenue])
```

**Total Profit**
```dax
Total Profit = SUM(SalesData[Profit])
```

## Dashboard Visualizations
1. Total Revenue – Card
2. Sales by Region – Clustered Column Chart
3. Top 5 Products by Profit – Clustered Bar Chart
4. Region Slicer for interactive filtering

## Project Files
- Power BI dashboard (.pbix)
- Excel dataset (.xlsx)
- Dashboard screenshot (.png)

## Learning Outcomes
Learned data importing, data cleaning, DAX calculations, data visualization, and interactive dashboard development using Power BI.
