## Introduction
By now, you should be familiar with data models, cardinality, cross-filter direction and working with advanced data models.

In this exercise, you must apply your knowledge of these concepts by configuring a Star schema for Adventure Works using Microsoft Power BI. By completing this exercise, you'll demonstrate your ability to:

- Improve data analysis.

- Enhance reporting and visualization.

- Ensure data standardization and consistency.

- Simplify data navigation.

## Adventure Works case study
Adventure Works wants to analyze its Sales data to generate insights into its business. It needs to create a data model using a Star schema. You can help the company to build this schema using the datasets within the workbook AdventureWorksData.


## Result Preview
- The **Sales** table is the **fact table** that records transactional details.
- The **Products, Region, and Salesperson** tables are the **dimension tables**.
- The cardinality is set to **Many-to-One** and that the cross-filter direction is set to **Single**.

Below is a snapshot of the Power BI repprt built based on the star schema:

![image](https://github.com/user-attachments/assets/320085e7-c790-43fc-a470-97db469485ba)
