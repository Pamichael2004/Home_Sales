# Home_Sales Homework:

1. Import the necessary PySpark SQL 

2. Read the `home_sales_revised.csv` data in the starter code into a Spark DataFrame.

3. Create a temporary table called `home_sales`.

4. Calculate the average price for a four-bedroom house sold for each year.

5. Calculate the average price of a home for each year it was built that has three bedrooms and three bathrooms.

6. Calculate the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet.

7. Determine the  "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query.

8. Cache your temporary table `home_sales`.

9. Check if your temporary table is cached.

10.  Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

11. Partition by the "date_built" field on the formatted parquet home sales data.

12. Create a temporary table for the parquet data.

13. Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

14. Uncache the `home_sales` temporary table.

15. Confirm that the `home_sales` temporary table is uncached using PySpark.

REFERENCES: Class Lessons Big Data 22 Activities