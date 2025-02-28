# SQL-PowerBI_BikeSales

## Overview

This project focuses on building a database from an Excel file, loading the data into Power BI, and creating dashboards for insightful analysis. 
The goal is to develop the **Bike Geeks Dashboard**, which provides insights into revenue trends, rider demographics, and seasonal patterns.

## Project Workflow
**1. Database Creation & Data Loading**
- Created a database *bike_db* in MySQL.

- Imported *bike_share_yr_0.csv* and *bike_share_yr_1.csv* into SQL.

- Merged tables using a LEFT JOIN with *cost_table* to include revenue and cost-related data.

- Selected key columns: *dteday*, *season*, *cte.yr*, *weekday*, *hr*, *rider_type*, *riders*, *price*, and *COGS*.

- Calculated **Revenue** and **Profit** using SQL queries.

**2.Data Connection to Power BI**

- Connected Power BI to MySQL database for real-time data retrieval.

- Ensured proper data transformation and modeling for seamless analysis.

**3.Dashboard Development**

- Created interactive visualizations to fulfill the project requirements:

  - **Matrix Table**: Displays **hourly sales data** across a week, filtered to working hours (8 AM - 9 PM).

  - **Line & Clustered Column Chart**: Tracks **riders, revenue, and profit trends** over time.

  - **Clustered Column Chart**: Compares **seasonal revenue** trends, showing that **season 3 has the highest revenue.**

  - **Donut Chart**: Visualizes the **percentage of casual vs. registered riders.**

  - **Card Visual**: Displays **total riders** and **Profit Margin** (calculated using a Power BI measure).

  - **Slicer**: Filters the dashboard by **year (2021 & 2022)** for trend comparison.

## Key Features & Technologies Used

- **SQL**: Data cleaning, transformation, and merging.

- **Power BI**: Interactive data visualization and dashboard creation.

- **Data Modeling**: Joined multiple datasets and ensured accurate measures.

- **Custom Calculations**: Created Profit Margin using DAX in Power BI.

## Insights
- Hourly revenue fluctuates, peaking during **working hours**.

- Revenue and profit trends show **seasonal variations**, with **season 3 generating the highest revenue.**

- **Registered riders** contribute more to revenue compared to casual riders.

- The **profit margin metric** helps evaluate profitability across different time periods.


## Conclusion

This project demonstrates how SQL and Power BI can be leveraged to transform raw data into meaningful business insights. By integrating a structured database with interactive dashboards, we can drive **data-driven decisions** for Bike Geeks.
