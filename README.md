# Superstore Sales Analysis With Python

## Project Overview

This project analyzes a Superstore sales dataset using Python to explore sales patterns across products, categories, customers, regions, states, and customer segments.

The analysis was performed in a Jupyter Notebook using Python, Pandas, NumPy, and Matplotlib.

## Objectives

The project focuses on answering business questions such as:

- What are the top-selling products within a category?
- Which U.S. states generate the highest sales?
- How are sales distributed across product categories?
- Which regions generate the highest total sales?
- Which states have the highest total sales?
- Which orders contain the highest number of line items?
- What is the average sales value for each customer segment in the United States?
- What is the date range covered by the dataset?

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- VS Code

## Data Preparation

The notebook includes several data-preparation steps:

1. Loaded the CSV dataset with Pandas.
2. Inspected the dataset dimensions and columns.
3. Standardized column names by:
   - Removing leading/trailing spaces
   - Replacing spaces with underscores
   - Converting names to lowercase
4. Removed the first index-like column.
5. Checked for duplicate records.
6. Removed duplicate records.
7. Checked for missing values.
8. Converted the order and shipping date fields to datetime values.

## Exploratory Analysis

The analysis includes:

### Top Products by Category

The notebook explores the highest-sales products within the Furniture category.

### Sales by U.S. State

U.S. states are grouped by total sales and the highest-performing states are visualized with a bar chart.

### Sales by Category

The dataset is examined by product category to understand the distribution of records across categories.

### Sales by Region

Total sales are calculated for each region.

The notebook produced the following regional totals:

| Region | Total Sales |
|---|---:|
| Central | $492,646.91 |
| East | $669,237.35 |
| South | $389,151.46 |
| West | $710,219.68 |

### Sales by State

States are grouped by total sales and the top-performing states are visualized.

### Orders with the Highest Number of Line Items

The notebook counts repeated order IDs to identify orders containing the largest number of line items.

### Average Sales by Customer Segment

The average sales value for each customer segment in the United States is calculated and visualized.

## Key Findings

The current analysis shows differences in sales performance across regions, states, categories, and customer segments.

The regional analysis shows that the West region has the highest total sales among the four regions in the notebook's calculated results, while the South region has the lowest.

Other findings are presented directly in the notebook through Pandas outputs and Matplotlib visualizations.

## Dataset

The dataset contains Superstore-style sales records with fields covering:

- Order information
- Customer information
- Location
- Product information
- Category and sub-category
- Sales
- Order and shipping dates

The notebook initially contained 9,800 rows and 18 columns.

## Project Structure

```text
Superstore-Sales-EDA/
│
├── data/
│   └── train.csv
│
├── notebooks/
│   └── Superstore_Sales_Analysis.ipynb
│
├── README.md

