# Home-Sales

## Background
I used SparkSQL to determine metrics about home sales data.  Then I used Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

## Analysis
What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

##Sources
1. https://stackoverflow.com/questions/58541146/rounding-of-double-value-without-decimal-points-in-spark-dataframe - I used this to help with rounding.

2. https://www.obstkel.com/spark-sql-date-functions - I used this to help me to extract year for date.
