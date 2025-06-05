## Introduction
By now, you should have a good understanding of the concept of profiling data and its practical applications to identify data anomalies. You covered the three primary data profiling operations, column quality, column distribution and column profile. In this exercise, you can apply your knowledge by using Microsoft Power Query to examine the valid, error, empty, min, max, unique, and distinct values in Excel spreadsheet rows, allowing you to identify the anomalies in the data.

## Case study
Adventure Works has recently acquired another bicycle business. Adventure Works’ CEO, Jamie Lee, has assigned a task to the sales department to ensure that the product data from the newly acquired company is validated, revised in quality factors, and ready for importing to the current company products. Your manager, Adio Quinn, has requested that you examine the data using Power Query by the factors of profile, quality, and distribution.

Adventure Works has provided you with an Excel file containing the newly acquired company’s product data called Other Company Products.xlsx. The dataset has some empty data in its **ProductKey** column. You also need to assess the distribution of the products by the product categories and detect potential anomalies in the **Price** column. To complete your task successfully, you must import the Excel file, transform the data in Power Query and assess the **Column quality, Column distribution, and Column profile** options in the **Data Preview** group.

- This exercise aims to help you to understand how to identify data anomalies by profiling data.

- By the end of this exercise, you’ll understand how to profile data in Power Query, and how to identify data anomalies.

## Result Preview
In this project, I used Column quality, Column distribution, and Column profile features in Power BI to explore and clean the dataset before building the data model.

- **Column quality**  
  Shows the percentage of **valid**, **error**, and **empty** values in each column.  
  → Helps identify missing or problematic data at a glance.

- **Column distribution**  
  Displays a visual representation of **value frequency** in the column.  
  → Useful for spotting **duplicates**, **outliers**, or **imbalanced categories**.

- **Column profile**  
  Provides detailed statistics for a selected column, including:  
  **Count**, **Distinct count**, **Min / Max**, **Average** (for numerical data)  
  → Helps you understand the data’s range and distribution.


These tools helped me:
- Detect and handle missing or invalid data
- Understand value frequency and identify duplicates
- Gain insights into data range and distribution

The results and visualizations shown in this project are based on this cleaned and profiled data.
<img width="1301" alt="image" src="https://github.com/user-attachments/assets/e61576d2-42cc-4cc7-8429-4d967c84a405" />
