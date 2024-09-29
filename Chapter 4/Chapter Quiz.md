# Chapter quiz questions
### Question 1
If you want to add a new customer to your database, which SQL statement should you use?
* `SELECT`
* `UPDATE`
* `INSERT`
Answer: `INSERT`

### Question 2
Janelle has a `Customer` database with customer information and an `Orders` database of orders that her customers made. How can she get the count of customers who have made orders?
* ```
SELECT COUNT(CustomerID)
From Customer;
```
* ```
SELECT COUNT(CustomerID)
From Orders;
```
* 
```
SELECT COUNT(DISTINCT CustomerID)
From Orders;
```
Answer: 
```
SELECT COUNT(DISTINCT CustomerID)
From Orders;
``` - The DISTINCT keyword will only count customers who have not already been counted.

### Question 3
Which SQL function should you use to join 2 or more strings into a new string?
* `CONCAT`
* `TRIM`
* `UPPER`

Answer: `CONCAT`