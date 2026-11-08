# zomatodashboard
Zomato Business Intelligence Dashboard
1. Project Description
Project Title: Zomato Business Intelligence Dashboard

The Zomato Business Intelligence project focuses on analyzing food delivery business data using PostgreSQL, Python, and Power BI. The main objective is to transform raw data into meaningful insights that help understand business performance, customer behavior, restaurant performance, sales, and delivery operations.

The project includes data cleaning, data preprocessing, database management, SQL analysis, and interactive dashboard development.

Tools & Technologies Used:
- Python – Data cleaning and preprocessing.
- PostgreSQL – Database creation, storage, and SQL queries.
- pgAdmin 4 – Database management.
- Power BI – Data visualization and interactive dashboards.
- DAX – Creating KPIs and business measures.
2. Key Project Features
1. Total Orders Analysis
2. Total Revenue Analysis
3. Average Order Value (AOV)
4. Delivered Orders Analysis
5. Average Delivery Time
6. Monthly/Quarterly Revenue Trends
7. City-wise Orders Analysis
8. Order Status Distribution
9. Top 10 Restaurant Performance
3. Challenges Faced During the Project
These are the major challenges encountered while developing the project:
Challenge	Solution
Duplicate records in CSV files	Removed duplicate records using Python.
Missing and invalid customer ages	Cleaned invalid values and handled missing data.
Incorrect customer ratings	Normalized ratings to a valid 1–5 range.
Negative delivery time values	Identified invalid delivery-time records for correction.
Foreign key constraint errors	Checked relationships between orders and other tables.
City name mismatches	Standardized city names such as Bangalore to Bengaluru.
PostgreSQL data import errors	Corrected CSV formats and column data types.
Inactive Power BI relationships	Used relationship analysis and DAX USERELATIONSHIP().
Dashboard development	Created DAX measures and interactive visualizations.

4. Project Outcome
The project successfully demonstrates how raw food delivery data can be transformed into a structured business intelligence solution.

The dashboard helps business users:
- Monitor overall sales and order performance.
- Identify high-performing restaurants.
- Understand customer ordering patterns.
- Track delivery performance.
- Compare business performance across cities.
