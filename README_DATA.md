# Microsoft Stock Dataset Analysis

## Dataset Overview
The dataset contains historical stock prices for Microsoft Corporation (MSFT) over a period from January 4, 2010, to December 30, 2016. It captures essential stock market features for each trading day, namely Open, High, Low, Close, and Volume.

## Objective
The objective is to analyze Microsoft's stock price behavior over time and to summarize its key statistical properties for further financial insights or machine learning modeling.

## Data Schema
| Column | Type | Description |
|:-------|:-----|:------------|
| Date | Date | Date of stock trading |
| Open | Float | Stock opening price |
| High | Float | Highest price of the day |
| Low | Float | Lowest price of the day |
| Close | Float | Closing price of the day |
| Volume | Integer | Number of shares traded |

## Assumptions
- No missing values were found; all records are complete.
- Prices are assumed to be recorded in USD.

## Storage Information
- Format: CSV (Comma-Separated Values)
- Number of rows: 1720
- Number of columns: 6
- File size: Approximately small (few MBs)

## Date Range
- From: 2010-01-04
- To: 2016-12-30

## Descriptive Statistics (Summary)
- Mean Open Price: 35.07 USD
- Mean High Price: 35.34 USD
- Mean Low Price: 34.77 USD
- Mean Close Price: 35.07 USD
- Average Volume: 44,294,408 shares
