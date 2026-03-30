Project Overview: Bright Coffee Shop Sales Analysis
The Bright Coffee Shop Sales Analysis is a comprehensive data analytics project designed to provide actionable business intelligence for a newly appointed CEO. As a Junior Data Analyst, the primary objective is to leverage historical transactional data to identify revenue drivers, optimize product performance, and uncover peak operational trends to support high-level decision-making.
Methodology and Architecture
The project follows a structured data lifecycle, beginning with Planning and Architecture using Miro. This stage involves designing a clear data flow that outlines the journey from the raw data source through an ETL (Extract, Transform, Load) pipeline. The architecture specifies DataBricks as the primary storage solution, ensuring data integrity and accessibility for the analysis phase.
Data Processing and Transformation
The technical execution takes place within Databricks, where raw Excel datasets are converted to CSV format for efficient processing. Key transformations include:
 * Data Cleaning: Standardizing numeric fields, such as converting European-style decimal commas to standard points.
 * Feature Engineering: Creating transaction_time_buckets to group sales into 30 or 60-minute intervals, allowing for granular time-series analysis.
 * Calculations: Using SQL to compute total_amount (unit price multiplied by quantity) and aggregating units sold by product category.
Analysis and Insights
Post-processing, the data is exported to Microsoft Excel or Power BI for visualization. The analysis focuses on three core pillars:
 * Revenue Performance: Identifying which specific products and categories generate the highest total income.
 * Temporal Trends: Pinpointing peak sales intervals to understand when the store performs best.
 * Inventory Optimization: Distinguishing between high-performing staples and underperforming items.
Strategic Recommendations and Delivery
The final phase involves a Presentation to the CEO, translating complex data into strategic growth opportunities. Recommendations include launching targeted marketing campaigns during slow intervals and implementing loyalty programs based on customer visit patterns. The complete project—comprising the Miro diagram, the processed dataset with pivot tables/charts, the PowerPoint presentation, and the original SQL code—is submitted via GitHub
