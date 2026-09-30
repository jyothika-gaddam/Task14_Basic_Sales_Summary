# Task 14 – Basic Sales Summary

## Description
This project calculates three basic sales KPIs using Excel and the Superstore dataset.

## Objective
Build a simple business summary using:
- Total Sales
- Average Sales
- Transaction Count

## Tools
- Microsoft Excel
- Superstore dataset

## KPIs

| KPI | Result |
|---|---:|
| Total Sales | 2,297,200.86 |
| Average Sales | 229.86 |
| Transaction Count | 10,800 |

## Excel Formulas Used

- **Total Sales:** `=SUM(Raw_Data!R2:R10801)`
- **Average Sales:** `=AVERAGE(Raw_Data!R2:R10801)`
- **Transaction Count:** `=COUNTA(Raw_Data!B2:B10801)`

## Workbook Structure

- `Raw_Data` – original Superstore transaction data
- `Summary` – 3 KPI summary and category sales chart
- `README` – task documentation

## Deliverables
- Summary sheet
- 3 KPIs
- Formula-based calculations
- Manual verification values
