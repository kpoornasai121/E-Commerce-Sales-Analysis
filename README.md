# Ecommerce Sales Analysis using Python & Excel

## Overview

This project is a comprehensive analysis of ecommerce sales data using Python and Excel, focusing on extracting valuable business insights through interactive dashboards and visualizations. The dataset covers multiple aspects of transactions, including sales, profit, product categories, state-wise sales, and customer segmentation.

## Key Features

- **Data Cleansing & Processing:**  
    Handled mixed date formats, missing values, and transformed raw data for analytical readiness using both Python and Excel.
- **Interactive Dashboard:**  
    Built a dynamic sales analysis dashboard in Excel, visualizing key metrics such as total sales, profit, order quantity, monthly trends, category and state-wise performance.
- **Advanced Analysis:**  
    Generated bar charts, waterfall charts, maps, and pie charts to highlight:
    - Monthly sales and profit
    - Sales by product category and sub-category
    - State-level sales distribution
    - Category-wise sales percentage
    - Top 5 sub-categories by sales
- **Filters & Drilldowns:**  
    Incorporated filters for year, region, and segment, enabling users to slice data as per their analytical needs.

## Tools & Technologies

- **Python**  
    - Used for data preprocessing (pandas, numpy) and initial exploratory analysis.
- **Excel**  
    - Utilized PivotTables, charts, and slicers to build the interactive dashboard.

## How to Use

1. **Data Preparation:**  
    - Clean and standardize raw data in Excel or using the provided Python notebook.
    - Ensure all date columns are properly formatted for consistency.

2. **Exploratory Analysis with Python:**  
    - Open [E-comm_DA.ipynb](https://github.com/kpoornasai121/E-Commerce-Sales-Analysis/blob/main/E-comm_DA.ipynb) in Jupyter Notebook.
    - Follow the notebook cells to preprocess the data, perform summary statistics, and export clean data for dashboarding.

3. **Building the Dashboard in Excel:**  
    - Import the cleaned data into Excel.
    - Create PivotTables for metrics such as sales, profit, and quantity by desired dimensions (month, category, state, etc).
    - Construct visualizations using Excel charts and configure slicers for interactive filtering.

4. **Dashboard Interaction:**  
    - Use slicers to filter by year, region, or segment and observe real-time metric updates.
    - Analyze the provided charts and maps to identify business trends and actionable insights.

## Dashboard Highlights

- **Total Sales, Profit, Quantity, Orders:**  
    See key metrics at a glance at the top of the dashboard.
- **Monthly Trends:**  
    Visualize fluctuations in sales and profit across the year.
- **Category & State Analysis:**  
    Compare category-wise performance and geographical sales distribution.
- **Sub-Category Drilldown:**  
    Identify which sub-categories drive the most sales.
- **Flexible Filtering:**  
    Focus your analysis using year, region, and segment slicers.

## File Structure

- [E-comm_DA.ipynb](https://github.com/kpoornasai121/E-Commerce-Sales-Analysis/blob/main/E-comm_DA.ipynb) — Python notebook for data cleaning, transformation, and analysis.
- [dashboard.xlsx](https://github.com/kpoornasai121/E-Commerce-Sales-Analysis/blob/main/DashBoard.xlsx) — Excel file with the interactive dashboard (not included here, to be created with above instructions).
- [dataset.csv](https://github.com/kpoornasai121/E-Commerce-Sales-Analysis/blob/main/dataset.csv) — Raw ecommerce sales data (replace with your dataset).

## Requirements

- Microsoft Excel (2016 or later recommended for full dashboard functionality)
- Python 3.x
    - pandas
    - numpy
    - jupyter (optional, for running the notebook)

## Credits

Developed as part of a business analytics and data visualization project to demonstrate end-to-end sales analysis using Python and Excel tools.
