# Instacart-Market-Basket-Analysis

Instacart Market Basket Analysis and Prediction

Project Objective
Use data on Instacart customer orders over time to predict which previously purchased products will be in a user’s next order.

From Instacart: "The applications: We hope the machine learning community will use this data to test models for predicting products that a user will buy again, try for the first time or add to cart next during a session."

About Instacart
Instacart is an American delivery company that operates a grocery delivery and pick-up service in the United States and Canada. The company offers its services via a website and mobile app. The service allows customers to order groceries from participating retailers with the shopping being done by a personal shopper.

Dataset
The dataset for this project is a relational set of files describing customers' orders over time. The dataset is anonymized and contains a sample of over 3 million grocery orders from more than 200,000 Instacart users. For each user, there are between 4 and 100 orders, with the sequence of products purchased in each order. The dataset also includes the week and hour of day the order was placed, and a relative measure of time between orders.

There are 6 tables in this dataset:

orders.csv

contains data about orders
order_products_train.csv

last order details (recommended training set)
order_product_prior.csv

prior orders details (data from user's previous orders)
products.csv

product details
aisles.csv

aisle details
departments.csv

department details
“The Instacart Online Grocery Shopping Dataset 2017”, Accessed from https://www.instacart.com/datasets/grocery-shopping-2017 on 4/05/2023

For this project, we will be using the order_products_train dataset combined with orders as both our training and testing data.

Order_product_prior datatable will be combined with the description tables (products, aisles and departments) as well as orders table to create features for our analysis.

We will also be conducting EDA on the users prior orders to see user preferences on historical data

The dataset is quite large and to be able to analyze it, I implemented a memory-saving function, which saved me about 50% of space
