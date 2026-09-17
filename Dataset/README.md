# Dataset README

This folder contains the raw data files used for the Madhav Store Dashboard project. The data is organized into two CSV files that are related through the common `Order ID` field.

## Files

### Details.csv

This file stores transactional sales details for each order.

Columns:
- Order ID
- Amount
- Profit
- Quantity
- Category
- Sub-Category
- PaymentMode

Use this file for:
- revenue analysis
- profit analysis
- category and sub-category performance
- payment method distribution
- quantity and order value trend analysis

### Orders.csv

This file stores customer and order metadata.

Columns:
- Order ID
- Order Date
- CustomerName
- State
- City

Use this file for:
- order timeline analysis
- sales by state and city
- customer segmentation
- regional performance analysis

## Relationship Between Files

The two datasets are linked by `Order ID`, which allows combined analysis such as:

- sales by state, city, and category
- profit trends by month and payment type
- customer-level revenue analysis
- regional performance across product categories

## Data Notes

- Date format in the order data appears to use `dd-mm-yyyy`.
- The dataset appears to represent retail or e-commerce store transactions.
- The project is designed for business intelligence/dashboard reporting and exploratory analysis.

## Typical Analysis Areas

- Sales performance
- Customer contribution
- Monthly profit trends
- Regional sales differences
- Product category mix
- Payment mode usage

## Data Quality

The files are CSV-based and ready for import into Excel, Power BI, or Python for analysis.
