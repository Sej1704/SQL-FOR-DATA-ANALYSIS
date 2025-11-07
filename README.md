**SQL Project: Customers and Orders Data Analysis**
**Overview**

In this project, I worked with two datasets — Customers and Orders — to understand how customer details connect with their purchase information.
The main goal was to clean, explore, and analyze the data using SQL, and then improve performance using database optimization techniques.

**Data Used**

Customers table: Contains customer details such as customer ID, unique ID, city, and state.

Orders table: Contains order information such as order ID, customer ID, order status, purchase date, approval date, and delivery date.

Each order is linked to a customer through the customer_id field.

**Steps Performed***
**1. Imported the Data**

I imported two CSV files — one for customers and one for orders — into MySQL.
Before importing the orders table, I ensured that all customer IDs in the orders file matched those in the customers table to maintain proper relationships between both tables.

**2. Explored the Data**

After importing, I viewed a few records from both tables to confirm that the data was loaded correctly.
I checked for missing values and duplicate entries to ensure the data was clean and ready for analysis.

**3. Performed SQL Analysis** 

I wrote different SQL queries to:

Find how many orders were placed by each city or state.

Identify which customers made the most orders.

Check which cities had the highest number of delivered orders.

Calculate the average delivery time for orders.

This helped in understanding customer behavior and order patterns.

**4. Created a View**

To simplify reporting and analysis, I created a View called order_customer_summary.
A view is like a virtual table that shows combined data from both the customers and orders tables.
It made it easier to quickly see each order along with the customer’s city and state without writing long SQL joins every time.

**5. Optimized Performance Using Indexes**

To make queries run faster, I added indexes to important columns such as:

customer_id in the orders table — this helps MySQL quickly find all orders for a given customer.

customer_state in the customers table — this improves filtering and searching by state.

Indexes are like shortcuts that speed up data retrieval, especially when working with large datasets.

**6. Key Learnings**

Through this project, I learned how to:

Import and connect CSV files into MySQL.

Use SQL queries to explore and analyze real-world data.

Create relationships between tables using foreign keys.

Build views to simplify repeated queries.

Improve query performance using indexes.

**Conclusion**

This task helped me understand how relational databases work in practice.
I learned to connect two datasets, analyze them efficiently, and optimize performance for better results.
It was a complete hands-on experience in data management, analysis, and SQL optimization.
