
Information about database(dbbookshop) tables - (Design a database scheme for optimized storage)

1) Table 1 : customer_master 	- 	To store the Customer details
2) Table 2 : product_master  	- 	To store the Product details
3) Table 3 : sales  		 	- 	To store the record of Product sold by Customer 									with sale date


Information about files

1) connection.php 			= 	Database connection using credentials
2) import.php 	  			= 	Import json file HTML form 
								(Read the json data from uploaded file and save it to the database)
3) index.php 				= 	- Simple page with filters for Customer, Product and 								    Product price
								- Output the filtered results in a table below the    filters
								- Last row for the total price of all filtered entries
4) response.php 			= 	Ajax response
5) dbbookshop.sql 			= 	SQL file
6) Code Challenge (Sales) 	= 	Main json file


