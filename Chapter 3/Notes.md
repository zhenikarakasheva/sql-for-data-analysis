# Working with dates
Most database managements systems will allow for many different data types for dates. In MySQL, the options are:
* DATE
* DATETIME
* TIMESTAMP
* YEAR

## DATE vs DATETIME
`DATE` will store the value as **YYYY-MM-DD**, whereas `DATETIME` will store it as **YYYY-MM-DD hh:mm:ss[.nnn]**

## How to extract year, month, day from a date

You can extract year, month and day from a date by using:

* `Year()` for the year - return an integer
* `Month()` for the month - returns an integer in the range [1,12]
* `Day()` for the day - returns an integer in the range [1,31]

## How to capture the current date and time
You can use `NOW()`.