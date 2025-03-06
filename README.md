# Coffee Shop Analysis
## INTRODUCTION:

This Excel workbook contains sales data for Maven Roasters, a coffee shop chain operating in three locations across New York City. It tracks sales, product performance, and customer trends. Using pivot tables, charts, and formulas, the workbook provides insights into revenue, expenses helping to optimize business decisions. 

## PROBLEM STATEMENT:

The task is to analyze and track the sales performance of a coffee shop using Excel. The goal is to create a sales report that includes weekly and monthly sales data, categorizing sales by product type and identifying trends or patterns in customer preferences and peak sales periods,to uncover actionable insights that can improve sales strategies.

## RECOMMENDED ANALYSIS:

1.How do sales vary by day of the week and hour of the day ?

2.Are there any peak times for sales activity ?

3.What is the total sales revenue for each month ?

4.How do sales vary across different store locations ?

5.What is the Average Price Per Order ?

6.Which products are the best selling in terms of Quantity & Revenue ?

7.How do sales vary by Product Category and Size ?

## DATASET OVERVIEW

transaction_id : Unique sequential ID representing an individual transaction

transaction_date : Date of the transaction (MM/DD/YY)

transaction_time : Timestamp of the transaction (HH:MM:SS)

transaction_qty : Quantity of items sold

store_id : Unique ID of the coffee shop where the transaction took place

store_location : Location of the coffee shop where the transaction took place

product_id : Unique ID of the product sold

unit_price : Retail price of the product sold

product_category : Description of the product category

product_type : Description of the product type

product_detail : Description of the product detail

## DATA CLEANING AND TRANSFORMATION:

In PowerQuery Editor,

1.Abbreviations such as "Lg," "Rg," and "Sm" were used to represent the size of products in the "product_detail" column.Instead created a new column named "size" to provide a clearer representation of product sizes. Sm : Small , Rg : Regular , Lg : Large.

2.Leading and Trailing spaces were eliminated from all columns, enhancing the cleanliness and uniformity of the dataset.

3.In transaction_time column  date values were removed, leaving only the time in HH:MM:SS format.

4.Added new column named "Total_bill" by multiplying the “unit_price” and “transaction_qty” for each entry,to get an overview of total sales.

5.Extracted the "day_of_week" and “month name” from the "transaction_date" column allowing for a detailed analysis of how sales fluctuate across different days and months. Similarly, extracting the “hour_of_day” from the "transaction_time" column enabling the identification of peak sales hours.

## INSIGHTS:


PEAK HOURS:The busiest hours for coffee sales are between 8:00 AM and 10:00 AM, indicating strong demand during morning hours. 

BEST SELLING PRODUCTS:Barista Espresso emerges as the best-selling product, followed by Brewed Chai Tea.

PERCENTAGE SALES BASED ON CATEGORIES:Coffee and Tea Categories account for the largest percentage share of sales which is about 39% and 29% respectively.

FOOTFALL DISTRIBUTION ACROSS DIFFERENT LOCATIONS:All stores exhibit almost similar level of footfall throughout the months, indicating a balanced distribution of customers across different locations. Similar footfall levels present equal opportunities for sales and revenue generation across all stores.

























