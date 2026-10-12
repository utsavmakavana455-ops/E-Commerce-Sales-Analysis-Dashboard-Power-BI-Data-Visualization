# E-Commerce Sales Analysis Dashboard | Power BI & Data Visualization

## Project Overview

Developed an interactive **E-Commerce Sales Analysis Dashboard using Microsoft Power BI** to analyze sales performance, revenue trends, customer behavior, and product performance using a dataset containing 1,000+ order records.

The project transforms raw e-commerce data into meaningful business insights through data cleaning, data modeling, DAX measures, KPI tracking, and interactive visualizations. The dashboard helps users monitor key performance indicators, identify top-performing products and categories, and understand sales patterns across different customer segments and locations.

## Project Objectives

- Analyze overall e-commerce sales performance and revenue.
- Monitor key business metrics through interactive KPI cards.
- Identify top-performing products and product categories.
- Understand customer purchasing behavior and sales contributions.
- Compare sales performance across cities and categories.
- Explore sales trends and patterns to support data-driven decision-making.
- Build an interactive dashboard with dynamic filters for detailed analysis.

## Tools and Technologies

- **Microsoft Power BI:** Dashboard development and data visualization.
- **Power Query:** Data cleaning, transformation, and preparation.
- **DAX (Data Analysis Expressions):** Creation of measures and calculated metrics.
- **Data Modeling:** Organizing data and establishing relationships where required.
- **Data Visualization:** KPI cards, bar charts, column charts, tables, and interactive slicers.
- **E-Commerce Dataset:** More than 1,000 order records for sales analysis.

## Key Performance Indicators (KPIs)

The dashboard focuses on important business metrics, including:

- **Total Revenue:** Measures the overall revenue generated from sales.
- **Total Orders:** Tracks the number of orders in the dataset.
- **Average Order Value (AOV):** Calculates the average revenue generated per order.
- **Total Quantity Sold:** Measures the total number of units sold.
- **Sales Performance:** Provides an overview of business performance across different categories, products, and locations.

## Dashboard Features

### 1. Sales Performance Analysis
Analyzes overall revenue and order performance to provide a clear overview of business activity. KPI cards allow users to quickly understand important sales metrics.

### 2. Revenue Analysis
Explores revenue distribution across product categories, locations, and other available dimensions. Visual comparisons help identify areas contributing significantly to total sales.

### 3. Product Performance Analysis
Identifies products generating higher sales and compares product-level performance. This helps highlight popular products and opportunities for further analysis.

### 4. Category-Wise Sales Analysis
Compares sales across product categories to understand which categories contribute most to overall revenue and sales volume.

### 5. Customer Insights
Examines customer purchasing patterns and revenue contributions using the available customer-related fields. These insights can help businesses understand customer activity and purchasing behavior.

### 6. Geographical Sales Analysis
Analyzes sales performance across cities or other available geographical fields to compare regional contributions and identify stronger-performing locations.

### 7. Interactive Filtering
Uses Power BI slicers and interactive visualizations to allow users to filter the dashboard by available dimensions, such as category and city. This enables more detailed analysis without creating separate reports for every view.

## Data Preparation and Analysis Workflow

1. **Data Collection:** Imported the e-commerce dataset containing 1,000+ order records.
2. **Data Cleaning:** Checked data quality and prepared fields for analysis using Power Query where required.
3. **Data Transformation:** Organized relevant columns, standardized data formats, and prepared the dataset for reporting.
4. **Data Modeling:** Configured the data structure and relationships where needed.
5. **DAX Measures:** Created measures for key metrics such as total revenue, total orders, average order value, and total quantity sold.
6. **Dashboard Development:** Designed interactive KPI cards, charts, tables, and slicers.
7. **Validation:** Checked the calculations and visual outputs against the underlying dataset.
8. **Business Analysis:** Used the dashboard to explore revenue distribution, product performance, category comparisons, and customer insights.

## Example DAX Measures

**Total Revenue**
```DAX
Total Revenue = SUM(orders[Revenue])
```

**Total Orders**
```DAX
Total Orders = DISTINCTCOUNT(orders[OrderID])
```

**Total Quantity Sold**
```DAX
Total Quantity Sold = SUM(orders[Quantity])
```

**Average Order Value**
```DAX
Average Order Value = DIVIDE([Total Revenue], [Total Orders], 0)
```

*Note: These measures assume the table is named `orders` and the relevant columns exist with the specified names. Adjust the names to match your actual dataset.*

## Business Value

This project demonstrates how raw e-commerce data can be converted into an interactive reporting solution. The dashboard supports:

- Faster monitoring of key sales metrics.
- Comparison of product and category performance.
- Identification of revenue patterns across locations.
- Exploration of customer purchasing behavior.
- More informed business decisions through data visualization.

## Skills Demonstrated

Power BI · DAX · Power Query · Data Cleaning · Data Transformation · Data Modeling · KPI Development · Sales Analysis · Customer Insights · Data Visualization · Business Intelligence · Analytical Thinking

## Conclusion

The E-Commerce Sales Analysis Dashboard demonstrates practical skills in **Power BI reporting, sales analytics, DAX calculations, and interactive dashboard development**. It showcases the ability to prepare data, calculate business metrics, design visual reports, and explore business performance through data-driven analysis.
