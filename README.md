# TASK3
Today, I worked with the sales table to perform data analysis using SQL. Below are the key tasks I completed:

Querying Customer Spending:

Used SELECT, FROM, and INNER JOIN to retrieve relevant data.

Applied GROUP BY with the aggregate function SUM(price) to calculate the total amount each customer spent on Zomato.


First Product Purchased by Each Customer:

Utilized RANK() OVER (PARTITION BY user_id ORDER BY created_date) to identify the first product purchased.

Combined it with WHERE clause to filter only the top-ranked (first) purchase per user.


Most Purchased Item on the Menu:

Employed SUBQUERY, DESC, COUNT() and TOP 1 logic to find the most frequently purchased item and the number of times it was bought across all customers.



These insights are extremely useful and serve as a strong foundation for building a dashboard or visual reports, enabling clearer business storytelling and better decision-making.
