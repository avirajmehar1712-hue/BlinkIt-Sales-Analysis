Blinkit Sales Analysis
Overview

This project analyzes Blinkit’s (formerly Grofers) sales dataset using Python, Pandas, NumPy, and Matplotlib. The goal is to uncover insights into sales performance across items, outlet types, and locations. The analysis includes data cleaning, exploratory data analysis (EDA), and visualizations to better understand the business and identify opportunities for optimization.

Objectives

Clean and prepare the dataset for analysis

Explore key sales metrics and patterns

Compare sales performance by item attributes (type, fat content)

Analyze the impact of outlet characteristics (size, location, establishment year) on sales

Visualize findings in an interpretable way

KPIs

Total Sales – Overall revenue generated

Average Sales – Mean revenue per transaction

Number of Items Sold – Count of items across all outlets

Average Rating – Mean customer rating of items

Dataset

Source: Kaggle Blinkit dataset (CSV file)

Shape: ~8,500 rows × 12 columns

Key Features:

Item_Identifier – Unique code for each item

Item_Weight – Weight of the item

Item_Fat_Content – Fat level (e.g., Low Fat, Regular)

Item_Type – Category of the product

Outlet_Identifier – Unique store code

Outlet_Establishment_Year – Year when the outlet was opened

Outlet_Size – Outlet size (Small, Medium, Large)

Outlet_Location_Type – Location type (Tier 1, Tier 2, Tier 3)

Outlet_Type – Type of outlet (Grocery store, Supermarket)

Item_Outlet_Sales – Sales of the item (target variable)

Steps Performed

Data Cleaning

Checked dataset size and structure

Handled missing values

Standardized categorical values (LF, low fat → Low Fat)

Exploratory Data Analysis (EDA)

Summary statistics of numerical and categorical features

Value counts and distributions

Visualizations (Matplotlib)

Bar charts → Sales by item type, fat content, outlet type

Grouped bar charts → Outlet tier vs. fat content sales

Line charts → Sales by establishment year

Pie/Donut charts → Sales by outlet size

Horizontal bar charts → Top-performing categories

Key Insights

Items with Regular fat content had higher sales than low-fat items

Tier 3 outlets generated the highest revenue

Medium-sized outlets performed better than small outlets

Snacks, dairy, and frozen foods contributed the most to overall sales

Tools & Libraries

Python

Pandas, NumPy

Matplotlib

Jupyter Notebook
