## Summary

### About Dataset

* The Supermarket Sales dataset is taken from kaggle.com.
* The dataset contains the following columns.
  - Invoice ID
  - Branch
  - City
  - Customer type
  - Gender
  - Product line
  - Unit Price
  - Quantity
  - Tax 5%
  - Total
  - Date
  - Time
  - Payment
  - COGS
  - Gross margin percentage
  - Gross income
  - Rating

### Screenshots of Dashboard

![This is an image of sales dashboard](https://github.com/ravindra0230/Projects/blob/main/Supermarket%20Sales/sales_dashboard.png?raw=true)

![This is an image of revenue dashboard](https://github.com/ravindra0230/Projects/blob/main/Supermarket%20Sales/revenue_dashboard.png?raw=true)

### General Analysis

* There are a total of 1000 rows with 1000 invoice ids which represent the total orders as 1000.
* The total quantity of products sold in these 1000 orders is 5510.
* The total revenue from all the orders is $332.97K.
* The toatl cost of goods and services is $307.59K.
* The total profit from these orders is $15.38K.
* Out of 1000 sales 50.1% are from member customers and 49.9% are from normal customers. The total revenue share is 49.2% for normal customers and 50.8% for member customers.
* The sales from male customers is 49.9% and that of the female customers is 51.1%. The total revenue from male customers is 48% and that from the female customers is 52%.
* Most of the sales happened on Saturday (164) followed by Tuesday (158). Least sales happened on Monday. The revenue also follows the same trend.
* Fashion and accessories product line has the most sales with 178 sales and Health and beauty has the least sales of 152. Food and bevereges has the highest revenue of $56K and Health and beauty has the least revenue of $49K.
* The city with most sales is Yangon (340) followed by Mandalay (332) and Naypyitaw (328). However, the revenue from Naypyitaw (which has the least sales) is the highest with $111K.
* Most used payment method is Ewallet wih 34.5% of the total sales and Cash payments with 34.4% of the total sales followed by Credit card with 31.1% of the total sales.
* The revenue from Credit card payment is 31.2%, from Cash payments it is 34.7% and by Ewallet it is 34.1%.

### Analysis by customer type in terms of sales

|                | Member             | Normal                                           | Sales       |
| :------------- | :----------------- | :----------------------------------------------- | :---------- |
| Product line   | Food and bevereges | Fashion accessories,<br />Electronic accessories | Most sales  |
| Product line   | Health and beauty  | Home and lifestyle                               | Least sales |
| Payment method | Credit card        | Ewallet                                          | Most sales  |
| Payment method | Ewallet            | Credit card                                      | Least sales |
| Day            | Tuesday            | Saturday                                         | Most sales  |
| Day            | Monday             | Monday                                           | Least sales |

### Analysis by customer type in terms of revenue

|                | Member                 | Normal                 | Revenue         |
| :------------- | :--------------------- | :--------------------- | :-------------- |
| Product line   | Food and Bevereges     | Electronic accessories | Highest revenue |
| Product line   | Electronic accessories | Health and beauty      | Least revenue   |
| Payment method | Credit card            | Ewallet                | Highest revenue |
| Payment method | Ewallet                | Credit card            | Least revenue   |
| Day            | Tuesday                | Saturday               | Highest revenue |
| Day            | Monday                 | Sunday                 | Least revenue   |

### Analysis by gender in terms of sales

|                | Male              | Female              | Sales       |
| :------------- | :---------------- | :------------------ | :---------- |
| Product line   | Health and beauty | Fashion accessories | Most sales  |
| Product line   | Sports and travel | Health and beauty   | Least sales |
| Payment method | Ewallet           | Cash                | Most sales  |
| Payment method | Credit card       | Ewallet             | Least sales |
| Day            | Wednesday         | Saturday            | Most sales  |
| Day            | Monday            | Thursday            | Least sales |

### Analysis by gender in terms of revenue

|                | Male               | Female             | Revenue         |
| :------------- | :----------------- | :----------------- | :-------------- |
| Product line   | Health and beauty  | Food and beverages | Highest revenue |
| Product line   | Food and beverages | Health and beauty  | Least revenue   |
| Payment method | Ewallet            | Cash               | Highest revenue |
| Payment method | Credit card        | Credit card        | Least revenue   |
| Day            | Saturday           | Tuesday            | Highest revenue |
| Day            | Monday             | Wednesday          | Least revenue   |

For more details, refer the Power BI file.
