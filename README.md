# KFC Sales Analytics

KFC Sales Data Analysis and Dashboard using Python and Excel.

## Project Overview

This project focuses on analyzing KFC sales data from 2023 to 2024. 
The raw data was cleaned and transformed using Python, followed by further data preparation, analysis, Pivot Tables, and dashboard creation in Excel.

## Data Sources

The project contains three main datasets:

- Customers Data
- Orders Data
- Products Data

## Data Cleaning and Preparation

The raw datasets were cleaned and prepared using Python.

### Python Data Cleaning

The following data cleaning and transformation activities were performed:

- Removed duplicate records
- Handled missing/null values
- Cleaned and standardized text data
- Cleaned customer and product information
- Cleaned date and time columns
- Converted columns into appropriate data types
- Standardized numerical columns
- Cleaned Price/Revenue values
- Prepared the data for further analysis

## Excel Data Preparation

After Python data cleaning, the cleaned data was further prepared in Excel.

The following columns and calculations were created:

- Delivery Duration column
- Month column
- Year column
- Total Revenue column
- Date-related columns
- Separate time-related fields
- Appropriate data types for different columns

### Delivery Duration

A separate Delivery Duration column was created to calculate the time taken between order time and delivery time.

### Month and Year

Separate Month and Year columns were created from the Order Date to support monthly and yearly analysis.

### Total Revenue

A separate Total Revenue column was created using the relevant sales values and quantities.

## Pivot Table Analysis

Pivot Tables were created in Excel to analyze the cleaned data.

The analysis includes:

- Total Revenue
- Monthly Sales Performance
- Yearly Sales Performance
- Product-wise Revenue
- Customer-wise Analysis
- Order Analysis
- Location-wise Analysis
- Order Type Analysis
- Delivery Time Analysis

## Dashboard

An interactive Excel dashboard was created to present the key insights from the analysis.

The dashboard includes:

- KPI Cards
- Total Revenue
- Total Orders
- Customer Analysis
- Product Analysis
- Monthly Sales Trends
- Yearly Sales Trends
- Delivery Duration Analysis
- Interactive Charts
- Pivot Table-based Visualizations

## Tools and Technologies

- Python
- Pandas
- NumPy
- Excel
- Pivot Tables
- Data Cleaning
- Data Analysis
- Data Visualization

## Project Workflow

Raw Data
↓
Python Data Cleaning
↓
Cleaned Data
↓
Excel Data Preparation
↓
Month & Year Columns
↓
Delivery Duration Calculation
↓
Total Revenue Calculation
↓
Pivot Table Analysis
↓
Dashboard Creation

## Repository Structure

KFC-Sales-Analytics/
│
├── Raw_Data/
│   ├── customers_raw.csv
│   ├── orders_raw.csv
│   └── products_raw.csv
│
├── Cleaned_Data/
│   ├── cleaned_customers.csv
│   ├── cleaned_orders.csv
│   └── cleaned_products.csv
│
├── KFC_Sales_Analytics_Dashboard_2023_2024.xlsx
│
└── README.md
