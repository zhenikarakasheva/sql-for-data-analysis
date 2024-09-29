# Chapter quiz questions
### Question 1
Raj has a database called `Orders` containing instances of `OrderID` and `CreationDate` for each order placed. How can he create a query that lists all the orders from '2016-05-01' to '2016-05-15'?
* `
SELECT OrderID, CreationDate
FROM Orders
WHERE CreationDate > Now()
`
* `
SELECT OrderID, CreationDate
FROM Orders
WHERE CreationDate BETWEEN '2016-05-01' and '2016-05-15'
`
* `
SELECT OrderID, CreationDate
FROM Orders
WHERE Month(CreationDate=5)
AND Year(CreationDate) = '2016'
`

Answer: 
`
SELECT OrderID, CreationDate
FROM Orders
WHERE CreationDate BETWEEN '2016-05-01' and '2016-05-15'
`
Raj can add the line "ORDER BY CreationDate" to order the output by date.

### Question 2
How will the MySQL `DATE` datatype store a date?
* YYYY-MM-DD hh:mm:ss
* hh:mm:ss
* YYYY-MM-DD

Answer: YYYY-MM-DD