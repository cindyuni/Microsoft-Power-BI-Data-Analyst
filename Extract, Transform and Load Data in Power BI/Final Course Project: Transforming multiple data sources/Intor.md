## Introduction
In this course, using Power BI, you covered the data extract, transform, and load process (ETL). You should now have a good understanding of:

- Connecting to data sources

- Column data types 

- Common data errors 

- Combining tables with merge and append 

- Advanced data transformation techniques 

- Loading and staging data 
- Profiling data by using column quality 
- Column distribution and column profile, and its practical application in identifying data anomalies. 

In this exercise, you will apply your knowledge in an end-to-end scenario by using Power Query to clean and transform multiple data sources and join and merge them. You’ll also examine the valid, error, empty, min, max, unique, and distinct values in the rows. This will allow you to identify the anomalies in the data. Finally, you will remove the data sources with anomalies. This exercise will help you understand how to clean, transform, join, and merge data sources in Power Query, and identify potential data anomalies by using data profiling tools.

## Case study
You are working as a data analyst at Adventure Works. Sales data is contained in two main tables, Order and OrderDetails. 


## Files
Adventure Works trades internationally and generates a large volume of sales data. To manage file sizes, the active Order table only includes data for the year 2023. Older data is stored in separate files for each year with the same fields and table structure. 

## The task
Your manager, Adio Quinn, asks you to conduct a detailed analysis of store sales. In the detail table, OrderDetails, there are multiple fields, but you only need ProductID, the quantity sold (which is in the field OrderQty), and the UnitPrice. Therefore, you are expected to remove unnecessary fields, and also eliminate empty rows, and identify any anomalies to remove those rows if necessary. After performing these tasks, you will append the two separate sales data sources together and then merge that with OrderDetails. Follow the steps below to complete the exercise.
