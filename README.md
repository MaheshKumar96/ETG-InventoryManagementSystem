# ETG-InventoryManagementSystem
Json-based-IMS -inventory management system where you can check the stock, billing, total inventory price.
##Introduction:
The inventory management system helps to track the purchases made and keep a record of the stock left. We can also generate bills in an efficient wau using Inventory Management System.

This project is mainly divided into two files:

Product insertion in Inventory: In this part, We create a record_dataSet.json file which contains all the stock items with details like product id , name, quantity, price. Here we can add new goods in the inventory and the records will be stored in records.json file.

2) Inventory_Purchase:
a) We enter the transaction or purchase details like product id,no. of items purchased,name of customer, mobile number of customer.
b) If the purchased items are available in inventory, then Bill is generated.
c) The detailes of the transactions are then stored in sales.json file.
Tools Used:
Python, json
