# Chapter quiz questions
### Question 1
If you have the following query, how can you add to the code to check for duplicate rows?
```
SELECT FirstName, LastName, COUNT(1)
FROM Customer
GROUP BY FirstName, LastName
```
* ` HAVING COUNT(1) > 1 `
* ` HAVING COUNT(1) = 1 `
* ` HAVING SUM(1) > 1 `

Answer: ` HAVING COUNT(1) > 1 `

### Question 2
How should you add to the following code block to check whether a product is both of the `Blueberry` variety and less than two dollars?
```
SELECT *
FROM
Product
WHERE
[Rest of code]
```
* `
Variety = 'Blueberry'
AND
Price < 2.00 
`
* `
Variety = 'Blueberry'
OR
Price < 2.00
`
* `
Variety = 'Blueberry'
AND
Price > 2.00
`
Answer: 
`
Variety = 'Blueberry'
AND
Price < 2.00
`
The logical "AND" operator will only allow the return of products that are of the "Blueberry" variety AND under two dollars.

### Question 3
You have a database `Customer` filled with data for `CustomerID`, `FirstName` and `LastName`, all with a `NOT NULL` constraint. What will be the output for the following code?
```
SELECT CustomerID,
FirstName,
LastName
FROM Customer
WHERE State IS NOT NULL
```
* no data
* first and last name of each customer
* contents of the `Customer` table

Answer: contents of the `Customer` table - this result will indicate that no state values are null.

### Question 4
Consider the simple data constraint example shown in the following code. What is the maximum size that a `CustomerID` can be for this table?
``` 
CREATE TABLE Customer(
  Customer ID int(4) NOT NULL,
  Name nvarchar(50) NOT NULL,
  Zipcode int NOT NULL
)
```
* 100
* 50
* 4

Answer: 4