# Retail-Sales-PowerBI-Dashboard
An interactive dashboard analyzing retail sales, profitability, and trends using Power BI.
# Retail Performance Dashboard: Sales, Profitability & Trends

## Objective
To develop an interactive dashboard using Power BI for analyzing retail performance across key dimensions including sales transactions, product details, site information, and customer demographics. The dashboard aims to provide insights into overall sales, profitability by product, sales trends, category performance, and regional contributions.

## Live Dashboard / Screenshots
Below is a screenshot of the dashboard. As this project was developed using Power BI Desktop.

*![image](https://github.com/user-attachments/assets/b5b3aa02-69e3-43a8-8d94-b05ad95174a5)
*

## Data Source
*https://www.kaggle.com/datasets/carebymanu/retail-insights-sales-inventory-and-customer-etc*

The data used for this project is the "Retail Insights: Sales, Inventory & Customer etc." dataset, sourced from [ Kaggle](https://www.kaggle.com/datasets/carebymanu/retail-insights-sales-inventory-and-customer-etc). This comprehensive retail dataset includes multiple CSV files covering site details, sales transactions, inventory levels, customer demographics, product information, and more. For this dashboard, the primary files utilized were `Sales_Data.csv`, `Product_Information.csv`, `Site_Details.csv`, and `Customer_Demographics.csv`. The data covers the period relevant to the dataset version used.


## Tools Used
* **Power BI Desktop:** For data import, transformation (Power Query), data modeling, DAX measure creation, and dashboard development.
* **DAX:** For creating calculated measures such as Total Revenue, Total Units Sold, and Total Gross Profit.
* **(Python/Jupyter Notebook):** For initial data exploration and overview.

## Key Features & Functionality
* **Data Modeling:** Established relationships between sales, product, site, and customer data tables.
* **Data Transformation:** Utilized Power Query to correct data types (especially dates) and prepare data for analysis.
* **Calculated Measures:** Developed DAX measures for key metrics like Total Revenue, Total Units Sold, and Gross Profit by Product.
* **Interactive Visualizations:**
    * KPI Cards: Displaying overall Total Revenue and Total Units Sold.
    * Profit & Revenue by Product: A combination chart analyzing profitability alongside revenue for products.
    * Sales Trends: A line chart showing Total Revenue over time (Year, Quarter, Month, Day).
    * Category Performance: A bar chart illustrating Total Revenue by Product Category.
    * Regional Sales: A donut chart showcasing Total Revenue distribution by State.
* **(Future Addition/To be implemented):** An interactive date range slicer to allow users to filter the entire dashboard by specific periods.*

## Skills Demonstrated
* Data Analysis & Visualization (Power BI)
* Data Modeling in Power BI
* Data Transformation (Power Query)
* DAX for Measure Creation
* Dashboard Design and Storytelling
* Retail Sales Performance Analysis
