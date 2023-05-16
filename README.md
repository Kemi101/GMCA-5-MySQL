# GMCA-5-MySQL

SQL 
This is the database that was given us, I downloaded and import create-databases SQL script into MySQL Workbench. Run the script and create databases. 
This was done as shown below. 
 
	![image](https://github.com/Kemi101/GMCA-5-MySQL/assets/131159967/aca1bee6-1650-421a-9f68-47e0dd003f60)

1.2	Add where customer_id=1 order by first_name to generate query
This query only generate order with customer_id of 1. Query as shown below  
select * from customers
where customer_id = 1
order by first_name;

#Another way of doing question one 
select * from customers
where customer_id = 1
order by first_name desc;

This is shown below 
![image](https://github.com/Kemi101/GMCA-5-MySQL/assets/131159967/1f804e3b-2d9d-4a56-88f9-51f09f6dd3c7)


I was asked to write a SQL query to return all the products in our database in the result set.  To show columns; name, unit price, and new column called new price which is based on this expression, (unit price * 1.1 ).
What I will doing is increasing the product price of each by 10%. With the query, I will show the original price and the new price.  This is shown below 

![image](https://github.com/Kemi101/GMCA-5-MySQL/assets/131159967/21d1a7d5-1de2-47a6-814d-dc84cdcbe8bb)

EER Diagram 
I went on the Database, click on reverse engineer, clicked on next and followed the instruction where then after I excute… then arranged the table.. 

![image](https://github.com/Kemi101/GMCA-5-MySQL/assets/131159967/d50520ac-6ee8-4cf2-a4bd-2cbe0cf8a0fd)


