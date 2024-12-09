# Superstore Sales Performance Dashboard

This repository contains a Power BI dashboard designed to visualize key sales metrics and insights. The dashboard provides an overview of total sales, items sold, discounts, and profits, along with detailed breakdowns by various dimensions such as region, state, city, and customer.

## Table of Contents

- [Overview](#overview)
- [Key Metrics](#key-metrics)
- [Data Cleaning Steps](#data-cleaning-steps)
- [Visualizations](#visualizations)
  - [Total Sales Page](#total-sales-page)
  - [Average Sales Page](#average-sales-page)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Sales Performance Dashboard is built using Power BI to help businesses track and analyze their sales data. It provides interactive and dynamic visualizations to gain insights into sales performance across different regions, states, ship modes, and customer segments.

## Key Metrics

- **Total Sales**: 449K
- **Total Items Sold**: 25K
- **Total Discount**: 1,080
- **Total Profit**: 69K
- **Average Sales**: 61.76
- **Average Items Sold**: 3.38
- **Average Profit**: 9.43
- **Average Discount**: 0.15

## Data Cleaning Steps

Before creating the dashboard, the following data cleaning steps were performed to ensure the quality and accuracy of the data:

### Removing Missing Values:
- Identified columns with missing values.
- Removed rows where critical fields (such as sales amount, customer ID) were missing.

### Handling Outliers:
- Used statistical methods (such as IQR, Z-score) to identify outliers in numerical fields.
- Removed or capped the outliers based on their impact on analysis.

### Removing Duplicates:
- Checked for duplicate records based on unique identifiers like transaction ID or customer ID.
- Removed duplicate records to ensure each transaction/customer is only represented once.

### Data Transformation:
- Converted data types to appropriate formats (e.g., dates, numerical).
- Created new calculated fields where necessary (e.g., profit margins, discount percentages).

These cleaning steps helped in preparing a robust dataset for accurate analysis and visualization.

## Visualizations

### Total Sales Page

- **Total Sales by Region**: Line chart displaying sales across Central, East, South, and West regions.
- **Total Sales by Ship Mode**: Donut chart showing sales distribution by different shipping modes.
- **Total Sales by Year**: Pie chart illustrating sales figures over the years.
- **Total Sales by State**: Bar chart ranking states by total sales.
- **Total Sales by Quarter**: Bar chart depicting sales for each quarter.
- **Total Sales by City and Category**: Bar chart showing sales by city and product category.
- **Customer Sales Performance**: Table detailing sales, items sold, profit, and discount for each customer.

### Average Sales Page

- **Average Sales by Region**: Line chart displaying average sales across regions.
- **Average Sales by State**: Bar chart showing average sales by state.
- **Average Sales by Quarter**: Bar chart illustrating average sales for each quarter.
- **Average Sales by Year**: Pie chart showing average sales figures over the years.
- **Average Sales by City and Category**: Bar chart displaying average sales by city and product category.
- **Average Sales by Ship Mode**: Donut chart showing average sales distribution by different shipping modes.
- **Customer Average Sales Performance**: Table detailing average sales, items sold, profit, and discount for each customer.

## Usage

To view and interact with the dashboard:

1. Clone this repository to your local machine.
2. Open the Power BI file (.pbix) using Power BI Desktop.
3. Refresh the data connections if needed and interact with the visualizations to explore the sales data.

## Data Sources

The data used in this dashboard is sourced from the superstore, which includes detailed records of sales transactions, customer information, and product details.

## Contributing

Contributions to this project are welcome. If you have suggestions for improvements or new features, please open an issue or submit a pull request.

