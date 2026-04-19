# Bright Coffee Shop Sales Analysis

## Project Overview
[span_0](start_span)This project focuses on analyzing transactional data for **Bright Coffee Shop** to provide actionable insights for the newly appointed CEO[span_0](end_span). [span_1](start_span)As a Junior Data Analyst, I have processed historical sales data to identify revenue drivers, peak operational hours, and product performance trends to support data-driven decision-making[span_1](end_span).

## Objective
[span_2](start_span)[span_3](start_span)The primary goal is to help the business grow revenue and improve product performance by answering key questions[span_2](end_span)[span_3](end_span):
* [span_4](start_span)Which products generate the highest revenue?[span_4](end_span)
* [span_5](start_span)What are the peak performance times for the store?[span_5](end_span)
* [span_6](start_span)What are the sales trends across various time intervals and categories?[span_6](end_span)

## Technical Workflow & Tools
[span_7](start_span)The project followed a structured data pipeline using the following tools[span_7](end_span):
* **[span_8](start_span)[span_9](start_span)Planning:** Miro (Data Flow & Architecture Diagrams)[span_8](end_span)[span_9](end_span)
* **[span_10](start_span)[span_11](start_span)Data Processing:** Databricks (SQL, ETL, and Data Transformation)[span_10](end_span)[span_11](end_span)
* **[span_12](start_span)[span_13](start_span)Analysis & Visualization:** Microsoft Excel (Pivot Tables and Dashboards)[span_12](end_span)[span_13](end_span)
* **[span_14](start_span)[span_15](start_span)Reporting:** Microsoft PowerPoint (Executive Presentation)[span_14](end_span)[span_15](end_span)

## Project Tasks

### 1. Planning & Architecture (Miro)
* [span_16](start_span)Designed a **Data Flow Diagram** outlining the source data, ETL pipeline, storage in Databricks, and final presentation layers[span_16](end_span).
* [span_17](start_span)Defined key metrics including total revenue, product performance rankings, and 30-minute time interval groupings[span_17](end_span).

### 2. Data Processing (Databricks)
* [span_18](start_span)Converted source Excel data to CSV and loaded it into the Databricks environment[span_18](end_span).
* **[span_19](start_span)Data Cleaning:** Cast `unit_price` to a proper decimal format (e.g., converting '3,1' to 3.1)[span_19](end_span).
* **[span_20](start_span)Feature Engineering:** * Created a `transaction_time_bucket` to group sales into 30-minute intervals[span_20](end_span).
    * [span_21](start_span)Calculated `total_amount` using the formula: `unit_price * transaction_qty`[span_21](end_span).
* [span_22](start_span)Used **SQL** to aggregate data by product types and time buckets[span_22](end_span).

### 3. Data Analysis & Visualization (Excel)
* [span_23](start_span)Exported the refined dataset to Excel for in-depth analysis[span_23](end_span).
* Developed a dynamic dashboard featuring:
    * [span_24](start_span)Total revenue and quantity sold by product category[span_24](end_span).
    * [span_25](start_span)Identification of peak time intervals and best-selling items[span_25](end_span).
    * [span_26](start_span)Visual charts and graphs to illustrate the sales story[span_26](end_span).

## Key Insights & Recommendations
[span_27](start_span)Based on the analysis, the following strategic recommendations were presented to the CEO[span_27](end_span):
* **[span_28](start_span)Inventory Management:** Increase stock levels for best-selling items to prevent stockouts[span_28](end_span).
* **[span_29](start_span)Targeted Marketing:** Launch promotional campaigns during identified slow time slots to boost traffic[span_29](end_span).
* **[span_30](start_span)Product Promotion:** Create bundles or discounts to promote underperforming products[span_30](end_span).
* **[span_31](start_span)Future Roadmap:** Automate daily reporting and implement a customer loyalty program based on peak usage data[span_31](end_span).

## Repository Structure
* `Miro_Plan/`: Architecture and data flow diagrams.
* `SQL_Scripts/`: SQL code used for data transformation in Databricks.
* `Dataset/`: Processed spreadsheet with pivot tables and charts.
* `Presentation/`: Final PowerPoint presentation and Methodology document.
*
