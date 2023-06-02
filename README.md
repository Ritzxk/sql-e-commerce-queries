# sql-e-commerce-queries
***First we create ERD for the e-commerce dataset using MySQL. <br>**
The description of the tables is as follows:

cust_dimen: This table contains information about customers. It defines their customer ID, customer name, city, state and the nature of their business.

shipping_dimen: This table stores the data of the shipping modes for each order ID placed by the customers. Its attributes are order_ID, ship_mode and ship_date.

orders_dimen: This table contains information about the orders placed by customers. It includes the Order_Number, order_ID, order_date and the order_priority. The order ID denotes the ID of the order placed by the customer. A customer may order multiple products together, where the ID of each product is given by the Order_Number. 

prod_dimen: This table contains information about the products of a company that are going to be sold to the customers. It includes information about product types and product subcategories. 

Market_fact_full: This table contains the details of each order, the customer who placed the order, the shipping details and the product details. It contains the foreign keys of all four tables described above.

**we fetch some relevant insight usinh SQL**
