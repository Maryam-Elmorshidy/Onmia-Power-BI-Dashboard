# Omnia | Sales & Profitability Analysis — Power BI

## 📌 Project Overview

Omnia is a Power BI data analysis project developed as part of the SkillEra learning track. The project focuses on analyzing the performance of a fictional company selling a variety of products, including electronics, home appliances, clothing, and books.

The project goes beyond the original task requirements by exploring additional Power BI features and analytical techniques to create an interactive dashboard that provides insights into sales performance, profitability, customer demographics, and geographical distribution.

## 🎯 Project Objectives

- Analyze overall sales and profitability.
- Identify top-performing products based on sales and profit.
- Explore sales trends across different years and quarters.
- Analyze customer demographics, including age groups and gender.
- Examine sales and customer distribution across cities, countries, and regions.
- Build an interactive dashboard that allows users to explore the data through filters and detailed visualizations.

## 🗂️ Data Model

The project uses a sales fact table and multiple dimension tables to organize the data and support analysis.

### Fact Table

- **Fact_Sales**: Contains sales transactions, including invoice numbers, invoice dates, customer and product IDs, quantities, unit prices, and total amounts.

### Dimension Tables

- **Dim_Category**: Product categories.
- **Dim_SubCategory**: Product subcategories and their corresponding categories.
- **Dim_Product**: Product details, costs, prices, and profit per unit.
- **Dim_Customer**: Customer information, including age, gender, and registration date.
- **Dim_Location**: City, state, and geographical location details.
- **Dim_Country**: Country and regional information.
- **Dim_Date**: Date attributes used for time-based analysis.

## 📊 Dashboard Pages

### 1. Main Page

A landing page featuring the Omnia logo and project title, with navigation buttons that allow users to move between the main dashboard sections.

### 2. Sales Dashboard

Focuses on overall sales performance through:

- **Total Sales**: Displays total sales of 90.58M.
- **Top 10 Products by Sales**: Identifies the highest-selling products, led by MacBook Pro and Dell Inspiron.
- **Sales by City**: Compares sales across different cities.
- **Sales by Time**: Explores sales performance across quarters and years (2023–2025).
- **Interactive Filters**: Allows users to filter the dashboard by country and year through a popup filter panel.

### 3. Sales Tooltip Page

A dedicated tooltip page that provides additional quarterly performance details when interacting with relevant visuals.

It includes:

- **QuarterOverQuarter**: Quarterly performance comparison.
- **Quarter Gross Rate**: Quarterly gross rate calculations.

This feature provides additional context without requiring users to navigate away from the main Sales Dashboard.

### 4. Profit Dashboard

Provides insights into profitability and product performance through:

- **Total Profit**: Displays total profit of 26.63M.
- **Profit Margin**: Displays a profit margin of 29.1%.
- **Profit by Age Groups**: Examines profit distribution across customer age groups.
- **Profit and Sales by Product**: Compares sales and profit for the top 10 products by profit.
- **Interactive Filters**: Enables filtering by country and year.

### 5. Customer Dashboard

Explores customer characteristics and geographical distribution through:

- **Total Customers**: Displays 2,000 customers.
- **Average Age**: Shows an average customer age of 44.
- **Customers by City**: Highlights cities with the highest customer counts.
- **Sales by Age Groups**: Compares sales across different customer age groups.
- **Gender Distribution**: Shows the distribution of customers by gender.
- **Region Filters**: Allows users to explore customer data across Europe, MENA, and North America.

## ⚙️ Tools & Techniques

- **Power BI Desktop** — Dashboard development and data visualization.
- **Power Query** — Data preparation and transformation where needed.
- **DAX (Data Analysis Expressions)** — Measures and calculations for sales, profit, profit margin, and time-based comparisons.
- **Data Modeling** — Organizing sales data and dimension tables for analysis.
- **Bookmarks & Buttons** — Creating interactive navigation and popup filter panels.
- **Tooltips** — Displaying additional analytical details within visuals.
- **Drill-through** — Exploring more detailed information from selected data points.
- **Conditional Formatting** — Highlighting values and improving data readability.
- **Market Basket Analysis (MBA)** — Exploring associations between products purchased together.
- **UNICHAR** — Enhancing visual indicators in dashboard elements.
- **Quarter-over-Quarter (QoQ) Analysis** — Comparing performance across quarters.

## 💡 Key Learnings

This project provided an opportunity to revisit previously learned Power BI concepts, experiment with additional features, and explore different approaches to data analysis.

It also reinforced the importance of asking meaningful business questions before choosing visualizations and selecting the appropriate measures to communicate insights effectively.

Not every technique explored during development was included in the final dashboard; some were tested as part of the learning process.

## 🙏 Acknowledgment

This project was originally assigned as part of the SkillEra learning track. I expanded on the original requirements by exploring additional concepts and applying different Power BI techniques using various learning resources.
