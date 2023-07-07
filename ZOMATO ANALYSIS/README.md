
# 📊 Zomato Data Analysis
This project is about SQL to perform exploratory data analysis. The data set is a dummy data set much like Zomato and with some minimal data. This project is basically done to gain some better knowledge and have a more tighter grip upon SQL. For this I have used Microsoft SQL server.

## 🗂 Creating Database
Created a database of a food website like Zomato with and inserted some dummy data to do some analysis upon the data. The database, named zomato_data contains 4 tables: goldusers_signup, users, sales, and product.

## 1️⃣ creating table goldusers_signup:
        drop table if exists goldusers_signup;
        CREATE TABLE goldusers_signup(userid integer,gold_signup_date date);
## 2️⃣ creating table product:
        drop table if exists product;
        CREATE TABLE product(product_id integer,product_name text,price integer);
## 3️⃣ creating table users:
        drop table if exists users;
        CREATE TABLE users(userid integer,signup_date date);
## 4️⃣ creating table sales:
        drop table if exists sales;
        CREATE TABLE sales(userid integer,created_date date,product_id integer);
## 📈 Some Analysis That Are Performed
From next are some important questions based on which analysis is performed. Some these questions are really important in improving upon any particular product, the business model.

## 1)what is total amount each customer spent on zomato?
![zomato Q 1)](https://github.com/nehal35/SQL-PROJECTSS/assets/108068313/a14434db-a49e-4319-98d2-093569db72c3)
## 2)How many days has each customer visited zomato?
![2](https://github.com/nehal35/SQL-PROJECTSS/assets/108068313/4801ebf7-ece3-4c5d-8379-ca2335f3242c)
## 3)what was the first product purchased by each customer?
![3](https://github.com/nehal35/SQL-PROJECTSS/assets/108068313/a64e2260-2d3d-4b97-b407-38bb3fa8fae6)
## 4)what is most purchased item on menu & how many times was it purchased by all customers ?
![4](https://github.com/nehal35/SQL-PROJECTSS/assets/108068313/3ea2e44e-3fc7-4fe9-b14c-452b8eb6f72a)
## 5)which item was most popular for each customer?
![5](https://github.com/nehal35/SQL-PROJECTSS/assets/108068313/98f815fc-ad8f-4a66-a42c-0fe05b198ace)
## 6)which item was purchased first by customer after they become a member ?
![6](https://github.com/nehal35/SQL-PROJECTSS/assets/108068313/584a5ff7-e54c-4337-af15-64bddd2ac45d)
## 7)which item was purchased just before customer became a member?
![7](https://github.com/nehal35/SQL-PROJECTSS/assets/108068313/50c8731c-f954-4092-9894-7ff9143f1bd6)
## 8)what is total orders and amount spent for each member before they become a member ?
![8](https://github.com/nehal35/SQL-PROJECTSS/assets/108068313/2439bfc6-ffa2-4a52-8a03-4aa3cc6ffc4d)
## 9)rnk all transaction of the customers
![9](https://github.com/nehal35/SQL-PROJECTSS/assets/108068313/2ea9fa0a-13c6-416e-8387-08a96ae7e806)
## 10)rank all transaction for each member whenever they are zomato gold member for every non gold member transaction mark as na
![10](https://github.com/nehal35/SQL-PROJECTSS/assets/108068313/e4520826-60f4-4fb4-8fb4-6709b77fca62)
