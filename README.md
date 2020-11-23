# Project 2: Data Insights and Strategy

Analysing transactional and customer data to identify behaviour trends and define a customer segmentation, informing a future sales strategy using MySQL, Tableau & Powerpoint

*Please note inspiration and data for this project came from the KPMG Innovation and Digital Solutions virtual internship offered on [Forage](https://www.theforage.com)*



## Resources Used
MySQL Version: 8.0.22 build 107609 CE (64 bits)  
Tableau Desktop Version: 2020.3.2 (20203.20.1018.2303) 64-bit  
Powerpoint Version: 16.43 (20110804)


### Brief

Sprocket Central Pty Ltd, a medium size bikes & cycling accessories organisation, needs help with its customer and transactions data. The organisation has a large dataset relating to its customers, but their team is unsure how to effectively analyse it to help optimise its marketing strategy.

Their marketing team is looking to boost business by analysing their existing customer dataset to determine customer trends and behaviour, with particular interest in which of customers of the 1000 in the 'new_customer_list' should be targeted to drive the most value for the organisation.

## Data Quality Assessment

The below table details which fields failed each of the Standard Data Quality Dimensions for each table.

| Table Name      | Accuracy      |  Completeness  | Consistency | Currency  | Relevancy | Validity  | Uniqueness  |
| ----------- | -----------        | ----------    |  ---------- | --------- | --------- | --------- | ----------- |
| Customer Address  | Title       |                |              |          |           |           |             |
| Customer Demographic  | Text     |               |              | deceased_indicator | default |           |             |
| Transactions  |  | online_order, brand, product_line, product_class, product_size, standard_cost, product_first_sold_date | product_id |           | order_status, profit (missing), customer_id |  list_price, product_first_sold_date |             |

## Data Insights and Customer Segmentation

## Presentation of Insights and Strategy
