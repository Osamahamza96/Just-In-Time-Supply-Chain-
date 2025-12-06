Just In Time – Supply Chain & Inventory Analytics
Power BI Graduation Project
Overview
This project provides an end-to-end analysis of the supply chain and inventory operations of Salford & Co., a company specializing in multi-warehouse logistics and Just-In-Time (JIT) inventory strategies.
Using a real operational dataset, the project aims to identify inventory inefficiencies, shipment delays, high-cost categories, and profit trends to support data-driven decision-making.

Dataset
28 columns
25,861 rows
Structured into 4 dimension tables and 1 fact table
Covers: orders, shipments, customers, products, and warehouse inventory.

Data Cleaning
Key cleaning steps included:
Removing unnecessary columns (Order Item ID, Order Time)
Fixing incorrect data types
Cleaning country names and removing special characters
Handling missing & duplicate values
Identifying products in inventory but not ordered (kept due to storage impact)
Removing unrealistic shipping durations (negative or >28 days)

Data Modeling
A Star Schema model was created with:
One PK in each dimension
Five FKs in the fact table
Many-to-one relationships across the model
This structure supports efficient analysis of shipments, sales, profit, and inventory flow.

 Key Insights
1. Shipment Performance
Late shipment rate is ~56%, indicating major logistics delays
Late shipments improved from 53% (2015 Q1) to 39% (2017 Q4)
Technology products have the highest delay rate (51%)

2. Sales & Profitability
Highest performance occurred in 2015, then declined sharply
Profit margin dropped over time due to reduced orders
Best-selling categories: Fan Shop, Apparel, Footwear, Golf

3. Inventory Analysis
Apparel has the highest storage cost (~$23,400)
Health & Beauty has the lowest storage cost
Fan Shop has the highest inventory cost/unit

4. Warehouse & Category Trends
Significant delay rates in high-volume departments (e.g., Fan Shop)
Some countries show consistently high late-shipment counts
Demand remained stable → the decline is likely supply-driven

Conclusion
The analysis reveals strong early performance but a clear decline driven by:
Falling order volumes
Loss of top-selling products
Long replenishment times
High late-shipment rates across all regions
Recommended actions include:
Strengthening inventory management processes
Reducing shipment delays
Improving replenishment speed for high-demand categories
Optimizing warehouse stock based on storage cost analysis
This Power BI project provides a comprehensive view of supply chain performance and supports strategic improvements for operational efficiency.

Team
Team Leader: Osama Hamza
Team Members: Haytham Abubakr – Mostafa Walid – Mohamed Samir – Bakheet Esraa – Ahmed Marwa – Essa Nermin Fahmy
Supervisor: Eng. Ahmed Abdel Latif

Tools Used
Power BI
Excel
DAX
Data Modeling
Data Cleaning / Transformation
