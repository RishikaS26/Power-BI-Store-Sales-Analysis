# Power BI Store Sales Analysis

## Project Overview

This project focuses on analyzing store sales data using Microsoft Power BI to understand product performance, sales trends, profitability, promotional discounts, and customer transactions.

The report includes interactive dashboards, data modeling, filtering, and comparative analysis to help explore business performance across different products, customers, dates, and promotional categories.

## Tools & Technologies

- **Microsoft Power BI** — Dashboard development and data visualization
- **Power Query** — Data transformation and cleaning
- **Data Modeling** — Relationships between fact and dimension tables
- **Excel** — Source data

## Data Preparation and Cleaning

The dataset was prepared in Power Query before building the report.

- Checked and corrected column data types.
- Merged tables where required.
- Handled null or missing values.
- Created custom columns for data preparation and calculations.

## Data Modeling

The report uses a fact table and dimension tables to organize transactional data and support analysis.

- Explored primary key and foreign key concepts.
- Established relationships between tables using matching key columns and compatible data types.
- Connected sales transactions with product, customer, and promotion information.
- Explored how table relationships affect filtering and report interactions.

## Dashboard Pages and Business Analysis

### 1. Overview Dashboard

Provides a high-level summary of store performance.

Key visualizations:
- Total sales, total profit, and order count.
- Sales trends over time.
- Promotion-category analysis.
- Relationship between profit and net sales.

### 2. Top and Bottom 5 Product Analysis

Identifies products with the highest and lowest performance across key business metrics.

- Top 5 and bottom 5 products by sales.
- Top 5 and bottom 5 products by profit.
- Top 5 and bottom 5 products by quantity sold.

### 3. Period Comparison

Enables comparison between two user-selected date ranges.

- Total sales comparison.
- Total profit comparison.
- Total quantity sold comparison.

### 4. Transaction-Level Analysis

Provides detailed order-level information through an interactive table.

Fields include customer ID, order ID, date, discount, discount percentage, net sales, price per unit, product ID, profit, promotion ID, total sales, and units sold.

Available filters include:
- Date
- Customer name
- Product name
- Promotion name

### 5. Data Model

Displays the relationships between the fact table and supporting dimension tables, illustrating how the data model supports cross-filtering and business analysis.

## Business Questions Addressed

1. Which products generate the highest and lowest sales, profit, and quantity sold?
2. How do sales trends change over time?
3. What is the relationship between profit and net sales?
4. How do sales, profit, and quantity sold compare across selected periods?
5. How do discounts vary across promotion categories?
6. How many orders are recorded?
7. What are the sales, profit, discount, and net sales details for individual orders?
8. Which cities contribute to sales?

## Key Skills Demonstrated

- Data cleaning and transformation
- Power Query
- Data modeling and table relationships
- Interactive report design
- Data visualization
- Sales and profitability analysis
- Time-based analysis
- Filtering and slicer configuration
- Business problem-solving

## Project Files

- Power BI report (`.pbix`)
- Source dataset (`.xlsx`)

## Conclusion

This project demonstrates how Power BI can be used to transform raw store data into an interactive analytical report. It combines data preparation, relationship modeling, visual analysis, and transaction-level exploration to support a better understanding of sales performance and business trends.
