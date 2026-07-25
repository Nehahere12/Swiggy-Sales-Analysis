SWIGGY SALES ANALYTICS & DATA WAREHOUSE DESIGN | MS SQL <br>
<br>
PROJECT OVERVIEW <br>
This project demonstrates end-to-end data engineering and analytics on a Swiggy food delivery dataset. It covers raw data extraction, data quality assurance, database normalization, dimensional modeling (Star Schema), and advanced SQL-driven business performance analytics. <br>
<br>
DATA WAREHOUSE ARCHITECTURE (STAR SCHEMA) <br>
- Fact Table (`FACT_SWIGGY_ORDERS`): Central transaction table storing key sales metrics (Order Volume, Revenue, Ratings) linked to all dimension tables via foreign keys. <br>
- Date Dimension (`DIM_DATE`): Captures temporal attributes (Day, Month, Quarter, Year, Day of Week) for time-series trend evaluations. <br>
- Location Dimension (`DIM_LOCATION`): Stores geographic hierarchy data (City, Area, Zone) for regional performance tracking. <br>
- Restaurant Dimension (`DIM_RESTAURANT`): Captures seller details including Restaurant Name, Cuisine Type, and Pricing Tiers. <br>
- Category Dimension (`DIM_CATEGORY`): Organizes menu groupings and food classification types. <br>
- Dish Dimension (`DIM_DISH`): Contains normalized item attributes, standardized dish names, and individual pricing baseline structures. <br>
<br>
DATA CLEANING & PIPELINE ACTIONS <br>
- Audit & Integrity Checks: Executed comprehensive validation scripts to detect and resolve null, blank, and duplicate records across source data. <br>
- String Standardization: Applied string manipulation to parse, clean, and normalize inconsistent dish and menu item names. <br>
- Referential Integrity: Standardized data types and constructed Primary Key / Foreign Key constraints linking dimension tables to the core Fact table. <br>
<br>
ANALYTICAL COVERAGE & KEY METRICS <br>
- Core KPIs: Total Orders Count, Gross Revenue, Average Order Value (AOV), and Average Customer Rating scores. <br>
- Temporal Analysis: Evaluated revenue trajectories across weekly, monthly, quarterly, and year-over-year cycles. <br>
- Operational Insights: Identified top-performing restaurants, most-ordered dishes, highest-grossing categories, and price-sensitivity effects on order volume. <br>
<br>
TECH STACK <br>
- Database Engine: Microsoft SQL Server <br>
- Core Concepts: Data Warehousing, Star Schema Design, ETL & Data Quality Checks, Advanced SQL Aggregations <br>
