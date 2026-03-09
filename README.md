# Ecommerce Sales Analysis Dashboard | Power BI

## Project Overview
This project involves the development of a comprehensive Sales Dashboard for a US-based Ecommerce company. The goal was to provide stakeholders with real-time insights into Year-to-Date (YTD) performance across various dimensions including profitability, customer categories, and regional performance.

## Business Requirements & KPIs
The dashboard addresses the following business scenarios:
* **KPI Banner:** Real-time tracking of YTD Sales, YTD Profit, YTD Quantity Sold, and YTD Profit Margin.
* **YoY Analysis:** Year-on-Year growth tracking for every KPI with integrated sparklines for monthly trend analysis.
* **Customer Segmentation:** Analysis of YTD Sales, PYTD Sales, and YoY growth across different customer categories using dynamic trend icons.
* **Geographic Performance:** State-wise and Region-wise sales performance to identify top and bottom-performing markets.
* **Product Insights:** Identification of Top 5 and Bottom 5 products by sales volume.
* **Shipping Optimization:** Analysis of sales by shipping type to determine the most efficient logistics methods.

## Technical Skills Applied
* **Data Connection:** Connected Power BI to MS SQL Server and flat files (CSV/Excel).
* **Data Transformation:** Performed extensive data cleaning and ETL using **Power Query**.
* **Data Modeling:** Developed a star schema model involving three tables and a custom **Date Table** for time-based analysis.
* **Advanced DAX:** Authored complex measures using functions such as `CALCULATE`, `SUMX`, `FILTER`, `VALUES`, `SELECTEDVALUE`, and `VAR`.
* **Time Intelligence:** Implemented `TOTALYTD`, `SAMEPERIODLASTYEAR`, and parallel period functions to enable YoY comparisons.
* **Data Visualization:** Utilized conditional formatting, dynamic icons, sparklines, and map-based visualizations to enhance report readability.

## Insights Generated
* Identified seasonal trends in sales performance, allowing for better inventory planning.
* Pinpointed high-churn customer segments through YoY category analysis.
* Highlighted regional shipping bottlenecks by comparing shipping type percentages across different states.

## How to View
1. Download the `.pbix` file from this repository.
2. Open using Power BI Desktop.