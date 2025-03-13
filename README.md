# NYC Taxi Trip Analysis Power BI Project

📌 Introduction
This project analyzes New York Yellow Taxi Trip Data for December 2023 and January 2024, providing key insights into trip patterns, profitability, and customer behavior. The goal is to create an interactive Power BI report using advanced DAX calculations, time intelligence measures, and field parameters.
📁 Data Source
NYC Taxi & Limousine Commission Trip Data
🔧 Data Import and Preparation
•	Data Import: Yellow Taxi Trip Records (PARQUET) datasets for December 2023 and January 2024.
•	Date Dimension Table: Created for enabling time intelligence calculations.
•	Taxi Zone Lookup Table (CSV) and Taxi Zone Shapefile (PARQUET) imported for geographic analysis.
•	Relationships: Established between the date table, taxi records, and geographic data.
🛠️ DAX Measures and Calculations
Key Metrics
•	Total Trips
•	Total Fare Amount
•	Average Trip Distance
•	Average Tip Amount
Advanced DAX Calculations
•	Peak Hours: Average trip duration and total trips by hour.
•	Popular Routes: Top pick-up and drop-off locations.
•	Trip Distance Analysis: Distribution of trip distances.
•	Tip Percentage: Average tip percentage based on fare and tip amounts.
•	Profitability by Location: Average fare and tip amounts for different zones.
Time Intelligence Calculation Groups
•	Year-to-Date (YTD)
•	Month-to-Date (MTD)
•	Previous Year (PY)
•	Same Period Last Year (SPLY)
Field Parameters
•	Enable dynamic metric switching in visuals.
🎯 Report Design and Visualizations
•	Interactive Dashboard: Designed with intuitive charts, maps, and tables.
•	Slicers and Filters: To enhance data exploration.
•	Geospatial Analysis: Taxi zones visualized using NYC Taxi Zone shapefiles.
🏗️ Solution Design Overview
Data Model Design
•	Star Schema with fact and dimension tables.
•	Fact Table: Yellow Taxi Trips.
•	Dimension Tables: Date, Taxi Zones.
Data Transformation
•	Power Query: Cleaned and transformed raw data.
•	Handling Missing Data: Assumptions made to fill gaps in zones and fares.
Performance Optimization
•	Aggregations: Pre-aggregated data for faster visuals.
•	Incremental Refresh: Set up for scalable data updates.
•	DAX Optimization: Measures fine-tuned for performance.
Scalability Considerations
•	Designed to scale from 2 months to 24 months of data.
•	Storage: Azure Data Lake or SQL Database recommended for large datasets.
•	Partitioning: Implemented for large tables.
Security and Access Control
•	Row-level security (RLS) implemented for restricted data access.
•	Report access limited to authorized users.

🚀 Future Improvements:
•	Real-time data integration with Azure Data Factory.
•	Predictive analytics using Python or R integration in Power BI.
•	User personalization for tailored insights.
This project demonstrates end-to-end Power BI capabilities from data preparation and modeling to advanced DAX and dynamic visualization offering a robust analytical tool for NYC taxi trip data insights.
🔗 Let’s dive into the data and uncover powerful insights!

