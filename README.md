# Financial Dataset Analysis For Sports Manufacuring Company

## Overview

This repository contains the dataset and analysis related to a sports manufacturer company's financial performance. The dataset includes detailed records of revenue and expenses across different business lines and subcategories. It is used to analyze and generate financial insights, including profitability and cost management.

## Dataset Description

### Columns

- **Year:** Year of the revenue or expense.
- **Month - Name:** Name of the month for the transaction.
- **Month - Sequence:** Numeric representation of the month.
- **Date:** Last day of the month for the transaction.
- **Business Line:** Business unit generating revenue or expense (e.g., Sportswear, Sports Equipment, Nutrition & Food Supplements).
- **Amount ($):** Revenue or expense amount in USD.
- **Expense Subgroup:** Detailed categories for expenses (e.g., OPEX, COGS).
- **Income / Expense Group:** Classification of revenue and expenses (e.g., Sales, Consulting Services, Other Income, OPEX, COGS, Interest and Tax).
- **Income or Expense:** Indicator of whether the amount is revenue or expense.

## Example Calculations

To understand the financial performance, the following calculations are performed:

- **Revenue:** Sum of all revenue groups.
- **COGS (Cost of Goods Sold):** Sum of all costs of goods sold.
- **Gross Profit:** Revenue minus COGS.
- **OPEX (Operating Expenses):** Sum of all operating expenses.
- **EBIT (Earnings Before Interest and Taxes):** Gross Profit minus OPEX.
- **Interest and Tax:** Total interest and tax expenses.
- **Net Profit:** EBIT minus Interest and Tax.

### Example Calculation

Given the following:

- **Revenue:** $100,000
- **COGS:** $20,000
- **OPEX:** $30,000
- **Interest and Tax:** $15,000

The calculations would be:

- **Gross Profit:** $100,000 - $20,000 = $80,000
- **EBIT:** $80,000 - $30,000 = $50,000
- **Net Profit:** $50,000 - $15,000 = $35,000

## Tools and Technologies

- **Power BI:** For creating interactive dashboards and visualizations.
- **ETL with Power Query:** For extracting, transforming, and loading data.
- **DAX (Data Analysis Expressions):** For complex calculations and data modeling.
- **ZoomCharts:** For advanced data visualizations.

