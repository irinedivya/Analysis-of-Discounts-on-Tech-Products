# Analysis-of-Discounts-on-Tech-Products
This project applies data cleaning and data quality methodologies to analyze discount patterns and their impact on average revenue for tech products between January 2017 and March 2018.
The goal of the analysis was to determine whether offering product discounts leads to higher sales and overall profitability. Through timeline and statistical analysis, the findings revealed that discounts up to around 30% were the most effective — providing a noticeable increase in sales — while larger discounts offered diminishing returns.

This insight helps inform data-driven pricing strategies, allowing businesses to optimize discount levels without negatively impacting revenue performance.

📊 Dataset & Sources: Data provided by WBS Coding School 

Link: https://drive.google.com/drive/folders/13OGwxS4tp-HjQRhCtpPfhJDnipnb90dm?usp=sharing

Data description

orders.csv – Every row in this file represents an order.  
order_id – a unique identifier for each order   
created_date – a timestamp for when the order was created    
total_paid – the total amount paid by the customer for this order, in euros   

State

“Shopping basket” – products have been placed in the shopping basket  
“Place Order” – the order has been placed, but is awaiting shipment details   
“Pending” – the order is awaiting payment confirmation   
“Completed” – the order has been placed and paid, and the transaction is completed.   
“Cancelled” – the order has been cancelled and the payment returned to the customer.    

orderlines.csv – Every row represents each one of the different products involved in an order.  
id – a unique identifier for each row in this file   
id_order – corresponds to orders.order_id   
product_id – an old identifier for each product, nowadays not in use   
product_quantity – how many units of that product were purchased on that order   
sku – stock keeping unit: a unique identifier for each product   
unit_price – the unitary price (in euros) of each product at the moment of placing that order   
date – timestamp for the processing of that product    

products.csv   
sku – stock keeping unit: a unique identifier for each product   
name – product name     
desc – product description   
price – base price of the product, in euros   
promo_price – promotional price, in euros      
in_stock – whether or not the product was in stock at the moment of the data extraction   
type – a numerical code for product type   

brands.csv
short – the 3-character code by which the brand can be identified in the first 3 characters of products.sku
long – brand name 

Key Findings & Results
Average discount of 30% shows the most growth in orders   
Holiday's impact orders and having lower discounts will not affect orders   
Top products were in repairs, upgrades and accessories   

Technologies Used

Programming language(s)

Python Key libraries and frameworks   
pandas, seaborn   

Environment:
Google Colab
Project Structure

Data files:

Cleaned Data :https://drive.google.com/drive/folders/17eSb1EA2aW0fK5pHEEhAnzdH8EeRqik_?usp=drive_link


Original Data:https://drive.google.com/drive/folders/13OGwxS4tp-HjQRhCtpPfhJDnipnb90dm?usp=sharing

Collaborators: Analysis was done with: Tanish:https://github.com/tanishtara & Jessica:https://github.com/jessicahiggins121


