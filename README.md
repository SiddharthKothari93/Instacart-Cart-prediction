# Instacart-Cart-prediction
**Team Members**: Siddharth Kothari, Siddartha Rao, Vishal Singh

**Project Summary**: Using the Instacart Public Datasets, we are focusing on solving following problems: 
a) Predicting which product customer will reorder again 
b) Clustering the customers based on their historical purchase behavior 
c) Recommending relevant products based on cluster and transactional history

**Project Introduction**: Want more personalized grocery recommendations to accommodate your shopping style? Want to save frequent trips to the market? Instacart is a same day grocery delivery app which provides delivery as fast as one hour. Instacart provides personal shoppers, who can shop and deliver groceries at your doorstep saving you time and money.

Instacart can benefit enormously from this project. Personalized recommendation and prediction will increase the user experience, allowing customers to move swiftly across products making it easier to shop. This will not merely reduce but also entices new customers by enabling them to reduce shopping time. The common behavior of the clusters can be used to predict and recommend which new product customer is most likely to buy and hence can boost the sales and profit.

**Data Set**: The dataset used was Instacart’s open sourced user’s transcational data, The Instacart Online Grocery Shopping Dataset 2017. The dataset is a relational set of files describing customers’ orders over time. The dataset is anonymized and contains a sample of over 3 million grocery orders from more than 200,000 Instacart users. For each user, it provide between 4 and 100 of their orders, with the sequence of products purchased in each order. It also provide the week and hour of day the order was placed, and a relative measure of time between orders.

The dataset consists of 6 files:
1) ’aisles.csv’: Contains aisle id and respective aisle name
2) ’departments.csv’: Contains department id and respective aisle name
3) ’order products prior.csv’: Contains transcational history of which product were purchased in each order, were they reordered, and thier add to cart order id and respective aisle name
4) ’order products train.csv’: Contains details of which product were purchased in the last order of few users, were they reordered, and their add to cart order id and respective aisle name
5) ’orders.csv’: Contains more details about each order like day of week, order number etc, Also tell which set (prior, train, test) does the order belong to.
6) ’products.csv’: Contains product details of product name, their aisle and department.
