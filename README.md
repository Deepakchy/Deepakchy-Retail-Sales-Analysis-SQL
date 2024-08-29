# Retail-Sales-Analysis-SQL
**Project Overview**

**Project Title:** Retail Sales Analysis

**Database:** retail_db

This project is designed to demonstrate SQL skills and techniques typically used by data analysts to explore, clean, and analyze retail sales data. The project involves setting up a retail sales database, performing exploratory data analysis (EDA), and answering specific business questions through SQL queries. This project is ideal for those who are starting their journey in data analysis and want to build a solid foundation in SQL.

### Objectives
1. Set up a retail sales database: Create and populate a retail sales database with the provided sales data.
2. Exploratory Data Analysis (EDA): Perform basic exploratory data analysis to understand the dataset.
3. Business Analysis: Use SQL to answer specific business questions and derive insights from the sales data.

### Project Structure

**1. Database Setup**
Database Creation: The project starts by creating a database named p1_retail_db.
Table Creation: A table named retail_sales is created to store the sales data. The table structure includes columns for transaction ID, sale date, sale time, customer ID, gender, age, product category, quantity sold, price per unit, cost of goods sold (COGS), and total sale amount.

**2. Data Exploration**
Record Count: Determine the total number of records in the dataset.
Customer Count: Find out how many unique customers are in the dataset.
Category Count: Identify all unique product categories in the dataset.

### 3. Data Analysis & Findings
 The following SQL queries were developed to answer specific business questions:

  Q.1 Write a SQL query to retrieve all columns for sales made on '2022-11-05<br /> 
  Q.2 Write a SQL query to retrieve all transactions where the category is 'Clothing' and the quantity sold is more than 10 in the month of Nov-2022<br /> 
  Q.3 Write a SQL query to calculate the total sales (total_sale) for each category.<br /> 
  Q.4 Write a SQL query to find the average age of customers who purchased items from the 'Beauty' category.<br /> 
  Q.5 Write a SQL query to find all transactions where the total_sale is greater than 1000.<br /> 
  Q.6 Write a SQL query to find the total number of transactions (transactions_id) made by each gender in each category.<br /> 
  Q.7 Write a SQL query to calculate the average sale for each month. Find out best selling month in each year<br /> 
  Q.8 Write a SQL query to find the top 5 customers based on the highest total sales.<br /> 
  Q.9 Write a SQL query to find the number of unique customers who purchased items from each category.<br /> 
  Q.10 Write a SQL query to create each shift and number of orders (Example Morning <=12, Afternoon Between 12 & 17, Evening >17).<br /> 

### Findings
**Customer Demographics:** The dataset includes customers from various age groups, with sales distributed across different categories such as Clothing and Beauty.<br /> 
**High-Value Transactions:** Several transactions had a total sale amount greater than 1000, indicating premium purchases.<br /> 
**Sales Trends:** Monthly analysis shows variations in sales, helping identify peak seasons.<br /> 
**Customer Insights:** The analysis identifies the top-spending customers and the most popular product categories.<br /> 

### Conclusion
This project serves as a comprehensive introduction to SQL for data analysts, covering database setup, data cleaning, exploratory data analysis, and business-driven SQL queries. The findings from this project can help drive business decisions by understanding sales patterns, customer behavior, and product performance.
