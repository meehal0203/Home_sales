# SparkSQL Analysis

### In this project, I will use knowledge of SparkSQL to determine key metrics about home sales data using Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

![image](https://github.com/meehal0203/Home_sales/assets/146681542/79ed5e0a-65fc-403f-adfc-bb2410ad4b2a)


### Steps taken:

* Import the necessary PySpark SQL functions for this assignment.

* Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

* Create a temporary table called home_sales.

### The following questions will be answered using SparkSQL:

* What is the average price for a four-bedroom house sold for each year, rounding off answer to two decimal places.

* What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off answer to two decimal places.

* What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off answer to two decimal places.

* What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off answer to two decimal places.

* Cache temporary table home_sales.

* Check if temporary table is cached.

* Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

* Partition by the "date_built" field on the formatted parquet home sales data.

* Create a temporary table for the parquet data.

* Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

* * Uncache the home_sales temporary table.

* Verify that the home_sales temporary table is uncached using PySpark.

* Download Home_Sales.ipynb file and upload it into "Home_Sales" GitHub repository.
