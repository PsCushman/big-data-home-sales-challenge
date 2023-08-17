# Big Data Challenge - A Home with a View


## Instructions

1. Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.
2. Import the necessary PySpark SQL functions for this assignment.
3. Read the home_sales_revised.csv data in the starter code into a Spark DataFrame. ![Screen Shot 2023-08-17 at 2 49 54 PM](https://github.com/PsCushman/big-data-home-sales-challenge/assets/122395437/a1643a4d-d88c-4f63-af14-ecca14e5211c)

4. Create a temporary table called home_sales. 
5. Answer the following questions using SparkSQL:
   - What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.  ![Screen Shot 2023-08-17 at 2 50 36 PM](https://github.com/PsCushman/big-data-home-sales-challenge/assets/122395437/f6edfc55-36f0-4442-90c9-66f0db0b006f)

   - What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.  ![Screen Shot 2023-08-17 at 2 51 00 PM](https://github.com/PsCushman/big-data-home-sales-challenge/assets/122395437/7b149b42-a981-4a5f-a271-9b8fd23a1846)

   - What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.  ![Screen Shot 2023-08-17 at 2 51 13 PM](https://github.com/PsCushman/big-data-home-sales-challenge/assets/122395437/2e2686c5-33cb-4516-95f0-e54e9b91fe42)

   - What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
6. Cache your temporary table home_sales.
7. Check if your temporary table is cached.
8. Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime. ![Screen Shot 2023-08-17 at 2 52 50 PM](https://github.com/PsCushman/big-data-home-sales-challenge/assets/122395437/58a25442-db71-4f53-b071-2284db8bcfe7)

9. Partition by the "date_built" field on the formatted parquet home sales data.
10. Create a temporary table for the parquet data. ![Screen Shot 2023-08-17 at 2 53 32 PM](https://github.com/PsCushman/big-data-home-sales-challenge/assets/122395437/e899a3b4-d0b3-4957-a1e7-65f2023a16d4)

11. Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime. ![Screen Shot 2023-08-17 at 2 53 53 PM](https://github.com/PsCushman/big-data-home-sales-challenge/assets/122395437/cffe7380-829a-4f42-be00-81e8ef8bae32)

12. Uncache the home_sales temporary table.
13. Verify that the home_sales temporary table is uncached using PySpark.  ![Screen Shot 2023-08-17 at 2 54 36 PM](https://github.com/PsCushman/big-data-home-sales-challenge/assets/122395437/84dd9803-0dab-45ae-8ff7-30e84be851c0)

14. Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.
