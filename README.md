# Ecommerce Sales Analysis Dashboard | Power BI

## 1. Project Overview & Business Case

Developed an end-to-end Power BI solution for a US-based Ecommerce company to solve a core business problem: the inability to efficiently track Year-to-Date (YTD) performance against historical data.

This project delivers a real-time visualization of key performance metrics, enabling stakeholders (from executives to logistics managers) to identify trends, pinpoint geographic bottlenecks, and make data-driven decisions to optimize the sales pipeline.

## 2. Live Dashboard View
![Ecommerce Sales Dashboard](./Dashboard.png)
> **Placeholder:** To add your screenshot, name your image file `Dashbaord.png`, upload it to this GitHub repository, and then uncomment the line below:


## 3. Measurable Results (Key Performance Metrics)

The finalized dashboard provides real-time visibility into the current snapshot of the business. By engineering a robust data model and time intelligence measures, the following state of the business was quantified:

* **Revenue Overview:** Tracking **$11.53M** in YTD Sales, marking a marginal change of -0.83% YoY.
* **Profitability:** Generated **$1.34M** in YTD Profit, representing a healthy **+4.50% Year-on-Year increase**.
* **Sales Volume:** Managed the sale of **107.2K** units YTD (-7.29% YoY).
* **Efficiency:** Achieved a consolidated YTD Profit Margin of **11.58%** (+5.37% YoY increase).

## 4. Business Insights & Analysis

By utilizing the drill-down capabilities of the dashboard, several critical insights were identified:

1. **Regional Supply Chain Analysis:** The **West Region** is the leading market (32.22% of Sales), while the **South Region** requires strategic focus (16.17% of Sales).
2. **Product Performance Optimization:** Identified top revenue drivers (e.g., Staples) vs. bottom performers (e.g., Rediform S.O.S. P...) by volume, informing inventory strategy.
3. **Logistics & Procurement:** Quantified that **60.51%** of all orders utilize "Standard Class" shipping, identifying the primary shipping cost driver for procurement analysis.
4. **Segmentation Trends:** Revealed that despite a marginal decrease in overall sales volume, overall **Profit is up by 4.5%**, indicating successful high-margin sales conversion.

## 5. Technical Stack & Key Functionalities

This project demonstrates proficiency across the entire data analysis lifecycle within the Microsoft Power BI ecosystem:

* **Data Acquisition & Integration:** Connected to multiple heterogeneous sources, including **MS SQL Server** and Flat Files (CSV).
* **ETL & Data Transformation:** Utilized **Power Query** for advanced data cleaning, including merging, filtering, and data type transformation.
* **Complex Data Modeling:** Developed a high-performance **Star Schema** with 3 fact/dimension tables and a custom, dynamic **Date Table** for comprehensive time intelligence.
* **Advanced DAX Analytics:** Engineered complex measures and calculations, including dynamic KPIs, Time Intelligence functions (`TOTALYTD`, `SAMEPERIODLASTYEAR`), and logical DAX (`CALCULATE`, `SUMX`, `VAR`, `FILTER`).
* **Visual Storytelling:** Implemented interactive sparklines for monthly trends, conditional formatting, dynamic icon indicators for YoY trends, and geospatial mapping (Map visualization).

## 6. How to Run

1. Clone this repository.
2. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Open the `.pbix` file included in this repository.
4. If the data sources are not dynamic, adjust the source paths in Power Query to match your local file structure.




