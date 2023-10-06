# Analysis of Chip Product Customer Segments 

Background

At a retail company, the Chips Category Manager wants to better understand the types of customers who buy chips and their purchasing behavior. As part of the data analysis team, I was instructed by my manager to make a customer analysis for the chips category. This analysis will be included in the strategic plan for the next half year.

Data Understanding

There is 2 dataset, transaction data and purchase behavior. The transaction data consists of 264836 rows and 8 columns. The following is an explanation of each column;

- DATE: the date when the transactions occurred.
- STORE_NBR: the store number or identifier where the transaction took place. Each store have a unique number.
- LYLTY_CARD_NBR: a loyalty card number associated with the customer making the transaction. Each customer have a unique number.
- TXN_ID: transaction identifier or unique transaction number for each purchase.
- PROD_NBR: product number. Each product have a unique number.
- PROD_NAME: description of the product. It is also contain information of size pack and brand name of product.
- PROD_QTY: the quantity of chips products purchased in each transaction.
- TOT_SALES: the total sales amount for each transaction.
  
The purchase data consist of 72637 rows and 3 columns, The following is an explanation of each column;
- LYLTY_CARD_NBR: a loyalty card number associated with the customer making the transaction. Each customer have a unique number.
- LIFESTAGE: customer attribute that identifies whether a customer has a family or not and what point in life they are at e.g. are their children in pre-school/primary/secondary school.
- PREMIUM_CUSTOMER: customer segmentation used to differentiate shoppers by the price point of products they buy and the types of products they buy. It is used to identify whether customers may spend more for quality or brand or whether they will purchase the cheapest options.
  
Define Problem Statement or Metric
- Who spends the most on chips (total sales) by lifestage and how premium their in purchasing behaviour
- How many customers are in each segment
- How many chips are bought per customer by segment
- What’s the average chip price by customer segment
- Who is the best customer segment being targeted
- What purchasing behavior by customer segment targeted

