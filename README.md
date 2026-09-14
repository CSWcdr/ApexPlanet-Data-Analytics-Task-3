# ApexPlanet Data Analytics Internship - Task 3

## Deep-Dive Analysis & Interactive Dashboarding

This repository contains Task 3 of the ApexPlanet Data Analytics Internship.

The objective of this task was to perform a deeper business analysis using customer segmentation and build an interactive dashboard for exploring key sales and customer insights.

## Task Objectives

- Define and analyze key business KPIs
- Perform customer segmentation
- Identify high-value customer groups
- Analyze revenue contribution across segments
- Explore revenue by age group, city, category, and product
- Build an interactive dashboard with filters and scorecards
- Present actionable business insights

## Dataset

The analysis uses the cleaned sales dataset prepared during the earlier internship tasks.

The dataset contains information such as:

- Order ID
- Order Date
- Customer ID
- Customer Name
- Age
- Gender
- City
- Product
- Category
- Quantity
- Unit Price
- Total Sales
- Age Group

## Customer Segmentation

Customers were segmented based on their total revenue contribution using quartile-based thresholds.

The three customer segments are:

- High Value
- Medium Value
- Low Value

This segmentation helps identify which customers contribute the most revenue and supports more targeted business strategies.

## Core KPIs

The following KPIs were used in the analysis:

1. **Total Revenue**
   - Sum of total sales generated across all transactions.

2. **Total Orders**
   - Number of unique orders in the dataset.

3. **Unique Customers**
   - Number of distinct customers.

4. **Average Order Value**
   - Total Revenue / Total Orders

5. **Total Quantity Sold**
   - Sum of all product quantities sold.

## Deep-Dive Analysis

The notebook includes analysis of:

- Revenue by Customer Segment
- Average Spend by Customer Segment
- Revenue by Age Group
- High-Value Customers by City
- Revenue concentration among high-value customers
- Customer-level revenue contribution
- Customer segmentation distribution

## Interactive Dashboard

An interactive dashboard was created using **Looker Studio**.

The dashboard contains:

- Total Revenue
- Total Orders
- Unique Customers
- Average Order Value
- Total Quantity Sold
- Monthly Revenue Trend
- Revenue by Customer Segment
- Revenue by Age Group
- Revenue by Category
- Top Cities by Revenue
- Top Products by Revenue

### Interactive Filters

The dashboard supports filtering by:

- Customer Segment
- Age Group
- Gender
- City
- Category

## Dashboard Link

**Live Dashboard:**  
PASTE_LOOKER_STUDIO_LINK_HERE

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Looker Studio
- Git
- GitHub

## Repository Structure

```text
ApexPlanet-Data-Analytics-Task-3/
├── notebooks/
│   └── task3_deep_dive_analysis.ipynb
├── dashboard/
│   └── task3_dashboard_preview.png
└── README.md
