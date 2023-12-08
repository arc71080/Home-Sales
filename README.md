# Home-Sales

## Background
I used SparkSQL to determine metrics about home sales data.  Then I used Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

## Analysis
What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

<img width="144" alt="Screenshot 2023-12-07 at 6 22 07 PM" src="https://github.com/arc71080/Home-Sales/assets/137009177/87d37e92-39ea-4319-89e7-877e02045466">

What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

<img width="201" alt="Screenshot 2023-12-07 at 6 22 18 PM" src="https://github.com/arc71080/Home-Sales/assets/137009177/c8c9eb43-eece-4656-b801-8e4891fafc86">

What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

<img width="198" alt="Screenshot 2023-12-07 at 6 22 29 PM" src="https://github.com/arc71080/Home-Sales/assets/137009177/bcab9d3d-5153-45c7-b9ce-7a8d43775b76">

What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

<img width="299" alt="Screenshot 2023-12-07 at 6 23 07 PM" src="https://github.com/arc71080/Home-Sales/assets/137009177/71030ec9-c5b2-46c2-a5e6-93dc65c2a886">

##Sources
1. https://stackoverflow.com/questions/58541146/rounding-of-double-value-without-decimal-points-in-spark-dataframe - I used this to help with rounding.

2. https://www.obstkel.com/spark-sql-date-functions - I used this to help me extract the year for the date.
