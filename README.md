
# Home Sales Analysis - Challenge 22

**Student:** Megan Neal  
**Instructor:** Brandon Knox

This notebook analyzes home sales data using PySpark SQL functions. The analysis includes:

- Initializing a SparkSession
- Reading the `home_sales_revised.csv` data
- Creating a temporary table for SparkSQL queries
- Running queries to calculate the average price for:
  - 4-bedroom houses by year
  - 3 bed/3 bath houses by year
  - Houses with 3 beds, 3 baths, 2 floors, and 2000+ sqft by year
  - Homes with view ratings having average prices ≥ $350,000 (with runtime comparison for cached and parquet data)


