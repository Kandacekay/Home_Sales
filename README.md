## Home Sales Analysis with Spark
This project involves analyzing a home sales dataset using Apache Spark. The tasks are divided into steps, each contributing to a comprehensive analysis of the dataset.

### Steps
1. Create Spark DataFrame:
- A Spark DataFrame is created from the home sales dataset.

2. Create Temporary Table:
- A temporary table named "home_sales" is created from the original DataFrame.

3. Query for Average Price of Four-Bedroom Homes:
- Write a query that returns the average price, rounded to two decimal places, for a four-bedroom house that was sold in each year.

4. Query for Average Price of Three-Bedroom, Three-Bathroom Homes:
- Write a query that returns the average price, rounded to two decimal places, of a home that has three bedrooms and three bathrooms.

5. Query for Average Price of Specific Home Criteria:
- Write a query that returns the average price of a home with three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet for each year built, rounded to two decimal places.

6. Query for View Rating based on Average Price:
- Write a query that returns the view rating for the average price for homes that are greater than or equal to $350,000, rounded to two decimal places. Include the run time for this query.

7. Create and Validate Cache:
- Create a cache of the temporary "home_sales" table and validate its correctness.

8. Run Cached Query and Compute Run Time:
- Run the query from step 6 on the cached temporary table, and compute the run time.

9. Create Partitioned Parquet Data:
- Create a partition of the home sales dataset by the "date_built" field, and read the formatted parquet data.

10. Create Temporary Table for Parquet Data:
- Create a temporary table of the parquet data.

11. Run Query on Parquet Data and Compute Run Time:
- Run the query from step 6 on the parquet temporary table, and compute the run time.

12. Uncache and Verify Temporary Table:
- Uncache the "home_sales" temporary table and verify its correctness.

Feel free to follow these steps and explore the detailed analysis of the home sales dataset using Apache Spark.
