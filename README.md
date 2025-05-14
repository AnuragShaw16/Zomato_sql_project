# Food Delivery App Database
📦 Features:

Track user signups and Gold membership upgrades.

Record sales/orders across different products.

Maintain a list of food items with prices.

Analyze trends like top users, frequent products, and order patterns.

Ideal for SQL learning and data analytics practice.


🗂️ Database Schema

users(userid, signup_date) – Stores user registration dates

goldusers_signup(userid, gold_signup_date) – Tracks premium membership adoption

sales(userid, created_date, product_id) – Records each food order

product(product_id, product_name, price) – Menu of available food items


🔍 Example Queries

Total sales by each user.

Users who became Gold members before placing any orders.

Most popular food items.

Revenue trends over time.

✅ Use Cases

SQL project or coursework

Backend prototyping for delivery apps

Data analysis and reporting exercises

