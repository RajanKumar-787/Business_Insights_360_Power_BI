# Business Insights 360 Power BI

## Project Overview
This project is part of Codebasics Data Analytics Bootcamp, where I used Power BI to analyze business performance across Finance, Sales, Marketing, and Supply Chain and deliver actionable insights through interactive dashboards.

##### [View Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOTIwZWFmMjMtYTA4NC00ZWE4LWFiZWQtMjc0ZDIxNzRiZjUxIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Table of Contents
- [Business Problem](#business-problem)
- [Solution Approach](#solution-approach)
- [Tech Stack](#tech-stack)
- [Dataset](#dataset)
- [Data Model Overview](#data-model-overview)
- [Power BI Concepts Learnt & Applied](#power-bi-concepts-learnt--applied)
- [Business Related Terms](#business-related-terms)
- [Power BI Dashboards](#power-bi-dashboards)
- [Key Insights](#key-insights--fy-2022)
- [Author & Contact](#author--contact)

## Business Problem
AtliQ Hardware, a fast-growing global consumer electronics company, relied on Excel for most of its business reporting. As the company expanded, managing large and scattered datasets in Excel became slow, error-prone, and difficult to maintain.

This lack of a unified reporting system caused inconsistent insights, delayed decisions, and significant financial losses in the Latin American division.

## Solution Approach
To overcome these challenges, AtliQ launched its first Power BI implementation through the Business Insights 360 Project, aimed at creating a unified 360° view of business operations across Finance, Sales, Marketing, and Supply Chain departments.

This end-to-end Power BI solution helps to:
- Deliver real-time business insights through interactive dashboards
- Enable data-driven decision-making at every management level
- Improve forecast accuracy, profitability, and operational efficiency

## Tech Stack
- **Project Documentation:** Mural (Project Planning and Charter)
- **Data Sources:** MySQL Database + Excel Files
- **ETL Tool:** Power Query
- **Data Modeling:** Snowflake Schema
- **Business Intelligence Tool:** Power BI Desktop
- **Data Analysis Language:** DAX (Advanced Measures & Calculated Columns)
- **Performance Optimization Tool:** DAX Studio
- **Deployment:** Power BI Service (Scheduled Refresh)

## Dataset
The dataset used in this project is provided for learning purposes as part of the course and is not publicly shared on GitHub due to course policy.

## Data Model Overview

This screenshot showcases the Snowflake Schema data model, built to ensure accurate aggregation and reliable reporting.

![Data Model](https://github.com/RajanKumar-787/Business_Insights_360_Power_BI/blob/2220a819929094d7d3f591b10dc26556429d320b/Images/Data%20Model%20Overview.png)

## Power BI Concepts Learnt & Applied
- Project Planning & Requirement Understanding
- Data Loading from MySQL and Excel
- ETL in Power Query (Data Cleaning & Transformation)
- Data Modeling (Star and Snowflake schema)
- Data Visualization & Interactive Dashboard Design
- Calculated Columns & DAX Measures
- Bookmarks & Page Navigation
- Dynamic Titles & KPI Indicators
- Conditional Formatting for Visual Highlights
- Custom Tooltips for Contextual Insights
- Used What-If Parameters to enable dynamic filtering
- Power BI Service (Publishing, Data Refresh & Sharing)
- Collaboration & Workspace Management

## Business Related Terms
- Gross Sales
- Pre-Invoice Deductions
- Net Invoice Sales
- Post-Invoice Deductions
- Net Sales
- COGS (Cost of Goods Sold)
- Gross Margin
- Gross Margin %
- Gross Margin per Unit (GM/Unit)
- Operating Expenses
- Net Profit
- Net Profit %
- YTD** (Year to Date)
- YTG** (Year to Go)
- Brick-and-Mortar
- ECommerce
- Direct Sales
- Retailers
- Distributors
- Consumers

## Power BI Dashboards

### 1. Finance View

This Finance View dashboard shows how the company is performing financially by tracking Net Sales, Gross Margin, and Net profit to understand overall business health and profitability.

![Finance View](https://github.com/RajanKumar-787/Business_Insights_360_Power_BI/blob/2220a819929094d7d3f591b10dc26556429d320b/Images/Finance%20View.png)


### 2. Sales View

This Sales View dashboard shows which customers, products, and markets generate the most sales, helping identify top performers and areas that need improvement.

![Sales View](https://github.com/RajanKumar-787/Business_Insights_360_Power_BI/blob/2220a819929094d7d3f591b10dc26556429d320b/Images/Sales%20View.png)


### 3. Marketing View

This Marketing View dashboard shows how ads, promotions, and discounts affected product sales, helping evaluate marketing effectiveness and its impact on Net Profit.

![Marketing View](https://github.com/RajanKumar-787/Business_Insights_360_Power_BI/blob/2220a819929094d7d3f591b10dc26556429d320b/Images/Marketing%20View.png)


### 4. Supply Chain View

This Supply Chain View dashboard shows how accurate the forecasts are, helping measure demand prediction effectiveness and maintain enough stock to meet customer needs.

![Supply Chain View](https://github.com/RajanKumar-787/Business_Insights_360_Power_BI/blob/2220a819929094d7d3f591b10dc26556429d320b/Images/Supply%20Chain%20View.png)


### 5. Executive View

This Executive View dashboard provides a complete business summary by combining Finance, Sales, Marketing, and Supply Chain insights to show overall company performance.

![Executive View](https://github.com/RajanKumar-787/Business_Insights_360_Power_BI/blob/2220a819929094d7d3f591b10dc26556429d320b/Images/Executive%20View.png)


## Key Insights | FY 2022

- The company achieved Net Sales of $3.74B, which is 353.5% higher than the benchmark LY, showing excellent revenue growth.
- Gross Margin stands at 38.08%, slightly above the benchmark 36.49%, indicating strong product-level profitability before other expenses.
- Despite strong sales and margins, high operating and marketing expenses pushed Net Profit to -14%, making the business unprofitable overall.
- Sales spiked during Oct–Dec due to festive seasons like Diwali and Black Friday, driven by strong marketing campaigns and seasonal discount offers.
- The company generated $3.74B in Net Sales but spent nearly the same amount on discounts, indicating a heavy reliance on discounting to attract customers.
- Forecast accuracy improved to 81.17% from 80.21% last year, showing better demand prediction and reduced risk of excess inventory or stockouts, leading to smoother business operations.
- India ($945.34M), USA ($770.26M), and South Korea ($300.59M) are the top-performing markets, contributing the highest sales.
- India ($945.34M) and North America ($1.02B) are the top-performing sub-zones, together contributing over 50% of total sales.
- Amazon ($496.88M), AtliQ Exclusive ($361.12M), and AtliQ eStore ($304.10M) are the top customers, showing a strong presence across online and offline channels.
- AQ Home All-in-1 Gen 2 ($213.02M), AQ BZ All-in-1 Gen 2 ($202.50M), and AQ Smash 2 ($154.31M) are the best-selling products, driving a major share of total revenue.
- The PC division contributes over 60% of total revenue, solidifying its position as the company's core business driver.
- Retailers accounted for 71.53% of total sales, highlighting the company's heavy dependence on retail partners.
- AtliQ's PC market share grew significantly from having no presence in 2018 to reaching 5.9% in 2022, showing remarkable growth and stronger brand positioning in the global PC market.


## Author & Contact

**Author:** Rajan Kumar  
**Email:** rajaninranchi787@gmail.com  
**GitHub:** [https://github.com/RajanKumar-787](https://github.com/RajanKumar-787)  
**LinkedIn:** [https://www.linkedin.com/in/rajankumar787/](https://www.linkedin.com/in/rajankumar787/)  

⭐ If you found this project helpful, please consider giving it a star!  
💬 Feedback and suggestions are always welcome!
