## Introduction
This project deals with deploying a **Recommender System (RecSys)** based on [Brazilian E-Commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce), using principles and techniques of **Machine Learning Operations (MLOps)**.

## Goals
- Analyze and select the best resources to build the recommendation system.
- Create a data store based on the Delta Lake architecture.
- Implement an MLOps architecture with automated pipelines.
- Provide a user interface integrated into the MLOps infrastructure.

## About the data
The Brazilian E-Commerce Public Dataset is a dataset created by [Olist](https://olist.com/pt-br/) that contains around 100.000 records about orders made between 2016 and 2018 on several Brazilian marketplaces.

**NOTE:** The data is real and has been anonymized to avoid any type of privacy and security issues.

The original dataset contains 8 tables and the relationships between them can be visualized in the schema below.

<img src="https://github.com/AllanSilva156/recsys-mlops/blob/main/data/schema.png?raw=true" alt="data schema" width="600" height="400">

A brief summary of the information contained in each table can be seen below.
1. `olist_customers_dataset.csv`: information about the customer and its location.
2. `olist_geolocation_dataset.csv`: information Brazilian zip codes and its lat/lng coordinates.
3. `olist_order_items_dataset.csv`: data about the items purchased within each order.
4. `olist_order_payments_dataset.csv`: data about the orders payment options.
5. `olist_order_reviews_dataset.csv`: data about the reviews made by the customers.
6. `olist_orders_dataset.csv`: core dataset.
7. `olist_products_dataset.csv`: data about the products sold by Olist.
8. `olist_sellers_dataset.csv`: data about the sellers that fulfilled orders made at Olist.

## References
KAGGLE. **Brazilian E-Commerce Public Dataset by Olist**. 2021. Disponível em: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce. Acesso em: 21 nov. 2023.
