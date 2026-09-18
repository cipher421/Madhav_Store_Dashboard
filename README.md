# Madhav Store Dashboard

A sales and business performance dashboard for an e-commerce/store dataset, built around transaction data and customer/order metadata. The project combines order-level details with customer geography and sales KPIs to provide a clear dashboard for understanding revenue, profit, product performance, and payment patterns.

## Project Overview

This repository contains the source data, a Power BI dashboard, and exported visual assets for a retail sales analysis project. The dashboard is designed to help answer questions such as:

- Which states contribute the most revenue?
- Which payment modes are most widely used?
- What is the monthly profit trend?
- Which product categories and sub-categories drive sales?
- Which customers contribute the most order value?

## Folder Structure

```text
Madhav_Store_Dashboard/
├── Dataset/
│   ├── Details.csv
│   └── Orders.csv
├── Madhav_Sales_Dashboard.pbix
├── Madhav_Sales_Dashboard.pdf
├── Madhav_Sales_Dashboard.png
├── README.md
└── .git/
```

## Files in the Project

### Dataset/

#### Details.csv
Contains transactional sales detail for each order, including:

- Order ID
- Amount
- Profit
- Quantity
- Category
- Sub-Category
- Payment Mode

This file is used for revenue/profit analysis, category performance, product mix, and payment mode trend analysis.

#### Orders.csv
Contains customer and order metadata, including:

- Order ID
- Order Date
- Customer Name
- State
- City

This file adds time and geography context so the dashboard can segment sales by region and customer.

### Madhav_Sales_Dashboard.pbix
The original Microsoft Power BI report file. This contains the dashboard visuals, slicers, and metrics used to analyze store performance.

### Madhav_Sales_Dashboard.pdf
An exported PDF version of the dashboard for quick sharing and presentation.

### Madhav_Sales_Dashboard.png
A screenshot preview of the dashboard design and KPI layout.

## Dashboard Highlights

The dashboard visualizes several key business metrics, including:

- Total Sales Amount
- Total Profit
- Total Quantity
- Average Order Value (AOV)
- Profit by Month
- Sales by State
- Quantity by Payment Mode
- Sales by Customer Name
- Quantity by Category
- Profit by Sub-Category

The visual design indicates a quarterly filter selection (Qtr 1 to Qtr 4) and an All option, allowing users to view trends across the whole dataset or a specific quarter.

## Data Relationship

The project uses a standard relational pattern between the two CSV files:

- Orders.csv provides order metadata and geography
- Details.csv provides financial and product transaction details
- Both files are connected through the common Order ID field

This makes it possible to perform combined analysis such as:

- sales by state and category
- profit by month and payment type
- quantity by city and sub-category
- customer contribution by region

## Suggested Use

1. Open the Power BI file to explore the full dashboard.
2. Review the underlying CSV files for raw data analysis.
3. Use the PDF or PNG export for presentations and stakeholder sharing.
4. If needed, extend the dataset with additional timestamps, product names, or customer segments for deeper analysis.

## Notes

- The dataset appears to cover a retail/store sales timeline in 2018.
- The dashboard is a business-intelligence exercise focused on descriptive analytics and sales monitoring.
- The project is suitable for learning Power BI dashboard design, data modeling, and retail KPI reporting.

## Summary

This folder contains a complete retail sales analysis project using Power BI and CSV-based source data. It presents a polished dashboard for exploring store performance, regional sales, payment behavior, and profit trends while keeping the underlying data available for further analysis and reporting.

## Output
<img width="1437" height="806" alt="Madhav_Sales_Dashboard" src="https://github.com/user-attachments/assets/0556cd11-860a-4ed4-9510-82196e34761c" />
