# Sales Data Cleaning & Analysis

## Project Overview

This project focuses on cleaning and preparing a sales dataset for analysis using Microsoft Excel.

## Objectives

- Identify missing values
- Check for duplicate records
- Correct data formatting issues
- Validate calculations
- Prepare data for business analysis

## Data Cleaning Tasks Completed

### Missing Values
- Investigated missing CouponCode records
- Identified blank entries using filters and COUNTBLANK()

### Duplicate Checks
- Examined OrderID records
- Verified that repeated OrderIDs represented valid transactions rather than duplicates

### Data Validation
- Verified TotalPrice calculations using:

TotalPrice = Quantity × UnitPrice

Example:

3 × 499.21 = 1497.63

## Analysis Performed

### Revenue by Product

| Product | Revenue (£) |
|----------|----------|
| Chair | 195,620.11 |
| Printer | 195,612.61 |
| Laptop | 192,126.56 |
| Tablet | 186,568.95 |
| Monitor | 175,651.41 |
| Desk | 167,459.93 |
| Phone | 151,722.39 |

### Quantity Sold

| Product | Quantity Sold |
|----------|----------|
| Chair | 562 |
| Printer | 542 |
| Laptop | 535 |
| Desk | 508 |
| Tablet | 497 |
| Monitor | 480 |
| Phone | 411 |

## Key Findings

- Chair generated the highest revenue.
- Printer generated the second-highest revenue.
- Phone generated the lowest revenue.
- Chair recorded the highest quantity sold.
- Phone recorded the lowest quantity sold.
- Cancelled orders represented the largest order status category.

## Tools Used

- Microsoft Excel
- Pivot Tables
- Filters
- COUNTBLANK()
- Data Validation

## Author

Lydia
Aspiring Data Analyst | MSc Digital Health
