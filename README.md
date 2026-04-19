# Bright Coffee Shop Sales Analysis

## Project Overview
This project focuses on analyzing transactional data for **Bright Coffee Shop** to provide actionable insights for the newly appointed CEO.As a Junior Data Analyst, I have processed historical sales data to identify revenue drivers, peak operational hours, and product performance trends to support data-driven decision-making.

## Objective
The primary goal is to help the business grow revenue and improve product performance by answering key questions:
* Which products generate the highest revenue?
* What are the peak performance times for the store?
* What are the sales trends across various time intervals and categories?

## Technical Workflow & Tools
The project followed a structured data pipeline using the following tools:
* **Planning:** Miro (Data Flow & Architecture Diagrams)
* **Data Processing:** Databricks (SQL, ETL, and Data Transformation)
* **Analysis & Visualization:** Microsoft Excel (Pivot Tables and Dashboards)
* **Reporting:** Microsoft PowerPoint (Executive Presentation)

## Project Tasks

### 1. Planning & Architecture (Miro)
*Designed a **Data Flow Diagram** outlining the source data, ETL pipeline, storage in Databricks, and final presentation layers
*Defined key metrics including total revenue, product performance rankings, and 30-minute time interval groupings.

### 2. Data Processing (Databricks)
* Converted source Excel data to CSV and loaded it into the Databricks environment.
* **Data Cleaning:** Cast `unit_price` to a proper decimal format (e.g., converting '3,1' to 3.1).
* **Feature Engineering:** * Created a `transaction_time_bucket` to group sales into 30-minute intervals.
* Calculated `total_amount` using the formula: `unit_price * transaction_qty`.
* Used **SQL** to aggregate data by product types and time buckets.

### 3. Data Analysis & Visualization (Excel)
* Exported the refined dataset to Excel for in-depth analysis.
* Developed a dynamic dashboard featuring:
* Total revenue and quantity sold by product category.
* Identification of peak time intervals and best-selling items
* Visual charts and graphs to illustrate the sales story.

## Key Insights & Recommendations
Based on the analysis, the following strategic recommendations were presented to the CEO
* **Inventory Management:** Increase stock levels for best-selling items to prevent stockouts.
* **Targeted Marketing:** Launch promotional campaigns during identified slow time slots to boost.
* **Product Promotion:** Create bundles or discounts to promote underperforming products.
* **Future Roadmap:** Automate daily reporting and implement a customer loyalty program based on peak usage data.

## Repository Structure
* `Miro_Plan/`: Architecture and data flow diagrams.
* `SQL_Scripts/`: SQL code used for data transformation in Databricks.
* `Dataset/`: Processed spreadsheet with pivot tables and charts.
* `Presentation/`: Final PowerPoint presentation and Methodology document.

