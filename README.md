# Power BI Assignment 2: DAX & Data Visualization – E-Commerce Sales Analysis

## Project Overview
This project focuses on analyzing e-commerce sales data using Microsoft Power BI. The objective is to transform raw data into meaningful insights through data modeling, DAX calculations, and interactive visualizations. The report helps analyze sales performance, profitability, sales targets, order distribution, and regional sales trends.

## Tools & Technologies
- Microsoft Power BI Desktop
- DAX (Data Analysis Expressions)
- Data Modeling and Relationships
- Interactive Charts and Visualizations

## Dataset
The project uses three datasets:
- **List of Orders:** Contains order dates, customer names, cities, and states.
- **Order Details:** Contains order IDs, sales amounts, profit, quantity, categories, and sub-categories.
- **Sales Target:** Contains monthly sales targets for different product categories.

## Tasks Performed

### 1. Data Modeling
- Established relationships between the List of Orders and Order Details tables using Order ID.
- Connected sales information with sales targets using relevant category and month fields where appropriate.
- Organized the data model to support accurate analysis across tables.

### 2. DAX Calculations
Created calculated columns and measures to analyze sales and profitability:
- **Category Type:** Combined category and sub-category into a single field.
- **Revenue per Order:** Calculated revenue using the assigned formula.
- **Sales Category:** Classified sales amounts as Above Average or Below Average.
- **Order Count:** Counted distinct orders.
- **Average Profit in Delhi:** Calculated average profit for orders associated with Delhi.
- **YTD Sales:** Analyzed year-to-date sales performance.
- **Actual Sales:** Calculated total sales amount.
- **Sales Target:** Calculated target values.
- **Profit Margin:** Calculated profit as a proportion of sales.
- **Total Sales Amount and Minimum Target:** Created measures for KPI and target analysis.

### 3. Data Visualization and Analysis

- **Sales Target vs. Actual Sales by Category:** Compared actual sales with assigned targets across product categories.
- **Monthly Sales Trend:** Used a line chart to explore sales patterns over time.
- **Profit Analysis:** Visualized profit data to compare performance across categories and sub-categories.
- **Max Profit Margin by Sub-Category:** Created a visual to examine profit margin differences among sub-categories.
- **Sales Performance Matrix:** Compared actual sales and sales targets across categories and months.
- **Geographic Sales Analysis:** Used a map visual to represent total sales by city and identify regional patterns.
- **Sales Distribution by Sub-Category:** Used a treemap to compare sales contributions from different sub-categories.
- **Order Count Analysis by State:** Used a funnel chart to visualize order counts across states.
- **Profit vs. Quantity by Sub-Category:** Used a scatter chart to explore the relationship between quantity sold and profit.
  
