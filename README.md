# Adventure Works Sales & Customer Performance Analysis 
## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Process](#process)
-[Tools & Technologies](#tools-&-technologies)
- [Key Insights](#key-insights)
- [Challenges & Solution](challenges-&-solution)

### Project Overview
 This project explores sales and customer performance using the Adventure Works dataset in Power BI. It highlights revenue trends, customer segments, and product-level insights through an interactive dashboard. The goal is to transform raw data into actionable insights that support business decision-making and performance tracking.

 ### Objectives
 - To perform an in-depth analysis of Adventure Works’ sales data to uncover trends, patterns, and performance drivers.  
- To evaluate customer segments and identify high-value groups contributing most to revenue growth.
- To assess product and regional performance to pinpoint profitable areas and underperforming segments.  
- To track key business metrics (revenue, profit, orders, return rate) and monitor performance over time.  
- To develop an interactive Power BI report that provides decision-makers with clear, actionable insights.

### Process  

1. **Data Understanding**  
   - Explored the Adventure Works dataset and identified key tables (Sales, Product, Customer, Date).  
   - Defined relationships to support sales and customer analysis.  

2. **Data Cleaning & Preparation**  
   - Removed duplicates, standardized formats, and handled missing values.  
   - Combined related tables using Power Query for a unified dataset.  

3. **Data Modeling**  
   - Built a star schema with Fact and Dimension tables.  
   - Created DAX measures for KPIs like Revenue, Orders, Profit, and Return Rate.  

4. **Data Visualization**
   - Developed interactive visuals in Power BI showing sales, products, and customer insights.  
   - Applied color formatting for growth/decline and added filters for region and segment.  

5. **Insights & Recommendations**  
   - Highlighted top-performing products and customer segments.  
   - Suggested actions to reduce returns and improve profitability.

  ### Tools & Technologies  

| Tool | Purpose |
|------|----------|
| **Power BI** | Data modeling, visualization, and interactive dashboard creation |
| **SQL** | Data extraction, transformation, and querying from the Adventure Works database |
| **DAX (Data Analysis Expressions)** | Creation of calculated measures and KPIs for deeper insights |
| **Power Query** | Data exploration, Data cleaning, merging tables, and shaping data for analysis |
| **GitHub** | Project documentation and portfolio hosting |

### Key Insights  

- Total revenue reached **$9M**, showing a **3.31% month-over-month growth**.  
- **Accessories and Bikes** generated the highest number of orders (9.6K) and strong revenue contributions.  
- The **Sport-100 Helmet** was the top-performing product, contributing over **$36K** in revenue.  
- **Professionals and Skilled Manual workers** emerged as the most valuable customer segments.  
- The **mid-income group** accounted for the largest order volume (~5.5K), indicating strong purchasing potential.  
- The **return rate** stood at **4%**, reflecting a **1.78% improvement** compared to the previous month.  
- Average **revenue per customer** was **$875**, suggesting consistent purchasing behavior.  
- Revenue growth came mainly from **accessories and repeat customers**, indicating strong brand retention.

 ###  Challenges and Solutions  

| Challenge | Solution |
|------------|-----------|
| **Complex Data Model:** The Adventure Works dataset contained many interrelated tables, making it difficult to link customer, product, and sales data accurately. | Built a **star schema data model** in Power BI and created clear relationships using primary and foreign keys. |
| **Data Quality Issues:** Inconsistent formats and missing values in customer and date fields affected analysis accuracy. | Used **Power Query** to clean and transform data, ensuring consistency before loading into Power BI. |
| **KPI Accuracy:** Initial DAX calculations produced inaccurate profit and return rate values. | Reviewed and refined **DAX measures**, validating results against raw data and SQL queries to ensure correctness. |



  

