<!--
* @Author: Surejya Suresh
-->

### Week 4 Practice Quiz : Test your knowledge on SQL
Grade received 100%

&nbsp;

#### Question 1

```
SELECT *
FROM employee
WHERE jobCode = 'FTE'
      AND LastName = 'James'
```

What does the asterisk (*) after SELECT tell the database to do in this query?
* Select all data that meets the criteria as stated in the query
* Select all data that meets the criteria as stated in the query, then multiply it
* **Select all columns from the employee table**
* Select the LastName column from the employee table
> SELECT * tells the database to select all columns from the employee table. The criteria in the WHERE clause tells the database what data in those columns the query should return.

&nbsp;

#### Question 2

```
SELECT *
FROM employee
WHERE jobCode = 'FTE'
      AND LastName = 'James'
```

In this query, the data analyst wants to retrieve data from which table?
* **employee**
* LastName
* jobCode
* James
> The data analyst wants to retrieve data from the employee table.

&nbsp;

#### Question 3

```
SELECT *
FROM employee
WHERE jobCode = 'FTE'
      AND LastName = 'James'
```

In this query, what will be retrieved from the database?
* All data from the FTE table, where the employee's LastName is James.
* **All data from the employee table, where the jobCode is FTE and the last name is James.**
* All data from the employee table, where the jobCode is FTE and the employee has any last name other than James.
* All data from the jobCode table, where the jobCode is FTE and the employee has any last name other than James.
> This query will select all data from the employee table, where the jobCode is FTE and the last name is James.

&nbsp;

#### Question 4
You are working with a database table that contains data about music artists. The table is named artist. You want to review all the columns in the table.
You write the SQL query below. Add a FROM clause that will retrieve the data from the artist table.

```
SELECT
*
```

How many columns are in the artist table?
* 9
* 5
* **2**
* 8
> The clause FROM artist will retrieve the data from the artist table. The complete query is SELECT * FROM artist. The FROM clause specifies which database table to select data from. There are two columns in the artist table.

&nbsp;

#### Question 5
You are working with a database table that contains data about music albums. You are only interested in data related to the album with ID number 277. The album IDs are listed in the album_id column from the album table.
You write the SQL query below. Add a WHERE clause that will return only data about the album with ID number 277.

```
SELECT
*
FROM
album
```

What is the name of the album with ID number 277?
* Vivaldi: The Four Seasons
* Mozart: Chamber Music
* Beethoven: Piano Sonatas
* **Bach: Goldberg Variations**
> The clause WHERE album_id = 277 will return only data about the album with ID number 277. The complete query is SELECT * FROM album WHERE album_id = 277. The WHERE clause filters results that meet certain conditions. The WHERE clause includes the name of the column, an equals sign, and the value(s) in the column to include. The name of the album with ID number 277 is Bach: Goldberg Variations.
