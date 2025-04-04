# Amazon-Sales-Data-Analysis using SQL and PowerBI

## Project Overview:

The major aim of this project is to gain insight into the sales data of Amazon to understand the different factors that affect sales of the different branches.

## About Data:

This dataset contains sales transactions from three different branches of Amazon, respectively located in Mandalay, Yangon and Naypyitaw. The data contains 17 columns and 1000 rows:

## Main Columns:
•	invoice_id: Unique transaction identifier
•	branch & city: Store location
•	customer_type: Type of customer (Member/Normal)
•	product_line: Category of products
•	unit_price: Price per unit
•	quantity: Number of units purchased
•	VAT (5%): Tax amount
•	total: Final amount paid
•	payment_method: Mode of payment
•	date & time: Transaction timestamp
•	rating: Customer feedback rating

## DataSet
- <a href="https://github.com/NageswaraRaoLam/Amazon-Sales-Data-Analysis/blob/main/Amazon_RawData.csv">Amazon_Sales_RawData</a>

## Approach Used

Data Wrangling: This is the first step where inspection of data is done to make sure NULL values and missing values are detected and data replacement methods are used to replace missing or NULL values.


1.1          Build a database

1.2          Create a table and insert the data.

1.3          Select columns with null values in them. There are no null values in our database as in creating the tables, we set NOT  NULL for each field, hence null values are filtered out.


Feature Engineering: This will help us generate some new columns from existing ones.


2.1           Add a new column named timeofday to give insight of sales in the Morning, Afternoon and Evening. This will help answer the question on which part of the day most sales are made.

2.2          Add a new column named dayname that contains the extracted days of the week on which the given transaction took place (Mon, Tue, Wed, Thur, Fri). This will help answer the question on which week of the day each branch is busiest.

2.3        Add a new column named monthname that contains the extracted months of the year on which the given transaction took place (Jan, Feb, Mar). Help determine which month of the year has the most sales and profit.


3. Exploratory Data Analysis (EDA): Exploratory data analysis is done to answer the listed questions and aims of this project.


## Business Questions:


1. What is the count of distinct cities in the dataset?

2. For each branch, what is the corresponding city?

3. What is the count of distinct product lines in the dataset?

4. Which payment method occurs most frequently?

5. Which product line has the highest sales?

6. How much revenue is generated each month?

7. In which month did the cost of goods sold reach its peak?

8. Which product line generated the highest revenue?

9. In which city was the highest revenue recorded?

10. Which product line incurred the highest Value Added Tax?

11. For each product line, add a column indicating "Good" if its sales are above average, otherwise "Bad."

12. Identify the branch that exceeded the average number of products sold.

13. Which product line is most frequently associated with each gender?

14. Calculate the average rating for each product line.

15. Count the sales occurrences for each time of day on every weekday.

16. Identify the customer type contributing the highest revenue.

17. Determine the city with the highest VAT percentage.

18. Identify the customer type with the highest VAT payments.

19. What is the count of distinct customer types in the dataset?

20. What is the count of distinct payment methods in the dataset?

21. Which customer type occurs most frequently?

22. Identify the customer type with the highest purchase frequency.

23. Determine the predominant gender among customers.

24. Examine the distribution of genders within each branch.

25. Identify the time of day when customers provide the most ratings.

26. Determine the time of day with the highest customer ratings for each branch.

27. Identify the day of the week with the highest average ratings.

28. Determine the day of the week with the highest average ratings for each branch.

## SQL File:

- <a href="https://github.com/NageswaraRaoLam/Amazon-Sales-Data-Analysis/blob/main/Amazon%20Sales%20Data%20Analysis.sql">Amazon_Sales_SQL_file</a>

## PowerBI File:

- <a href="https://github.com/NageswaraRaoLam/Amazon-Sales-Data-Analysis/blob/main/Amazon%20Sales%20Data%20Analysis_PowerBI.pbix">Amazon_Sales_PowerBI_file</a>

## Amazon Sales Analysis Dashboard

![Image](https://github.com/user-attachments/assets/cb6e800e-fea7-431b-b4b0-eb7f029cd1f1)

## Recommendations:


•	Feb month sales are down hence change the market strategy
•	Health and Beauty segments has recorded less sales. Keep focus on female customers as we have received less order from them
•	Home and lifestyle has ranked bottom. Improve the quality to gain the customer satisfaction
•	Announce special offers to improve the sales on Monday
•	Convert the normal customers to members by providing extra benefits
•	Sales in the afternoon and evening are high. Grab the extra attention in the morning 


