## Introduction
Imagine you've just walked into Adventure Works headquarters as a data analyst, ready to tackle the day's challenges. You get an email notification from your manager. She asks you to evaluate samples and descriptions of diverse data blocks using Microsoft Excel. The data will eventually be loaded into Power BI. As you scan the task, you understand this isn't just about analyzing data; it's about transformation, about making the data ready to answer the right questions. 

This exercise will assist you in understanding how to evaluate and transform data at source using Microsoft Excel. You will explore specific scenarios of untidy data and learn how to handle missing values, inconsistent formats, and errors to make your data analysis ready. 

By the end of this exercise, you’ll understand how to derive meaningful insights from diverse datasets and answer critical business questions by working with data in the Sales, Inventory, and Customer Feedback CSV files.

## Sales Dataset: What is the total sales value per product?
First, you are presented with the Sales dataset. It needs to be more organized. It has missing TransactionIDs, SalesAmounts, and text in place of numbers. The analysis question to answer is: “What is the total sales value per product?” To answer this, you'll have to fill in missing SalesAmounts, transform textual entries into numbers, and then aggregate the sales by product. The transformations you implement here will directly feed into the sales trends that Adventure Works will soon uncover.

## Inventory Dataset: What is the stock level for each bike category?
Next up is the Inventory dataset. Here, you notice missing ProductNames and Categories, and inconsistencies in RestockingFrequency. The task is to figure out: What is the stock level for each bike category? To discover this, you need to standardize Category and fill in missing product details. The transformed data will subsequently support improved inventory management strategies at Adventure Works.

## Customer Feedback Dataset: What is the average feedback score for each product?
Finally, you check the Customer Feedback dataset. Here, FeedbackScores are irregular, dates are erroneous, and some feedback entries are missing altogether. Your analysis question is: What is the average feedback score for each product? This question requires you to correct the irregularities in FeedbackScores, fix erroneous dates, and determine how to treat missing feedback entries. These transformations will give Adventure Works the knowledge it needs to enhance customer satisfaction.
