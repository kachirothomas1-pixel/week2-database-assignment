# Week 2 Assignment: Introduction to SQL

This repository contains SQL solutions for the five questions in the Week 2 Introduction to SQL assignment. The queries use the `sales` database.

## Requirements

- MySQL Server
- MySQL Workbench or another MySQL client
- The supplied `sales` database, including its tables and data

## Database setup

If the database is already installed, confirm that it exists and select it:

```sql
SHOW DATABASES;
USE sales;
```

If `sales` is not listed, import the database and its data using the setup video and database file provided with the assignment. The queries will not return the expected results until the database has been imported.

## Assignment solutions

The file `week2_assignment.sql` contains the five requested queries:

1. Retrieve payment check number, payment date, and amount.
2. Find orders with status `In Process`, sorted by order date from newest to oldest.
3. Find employees with the job title `Sales Rep`, sorted by employee number from highest to lowest.
4. Retrieve every column and row from the offices table.
5. Retrieve the five products with the lowest buy price, displaying product name and quantity in stock.

## How to run

1. Open MySQL Workbench or your preferred MySQL client.
2. Connect to your MySQL server.
3. Open `week2_assignment.sql`.
4. Run the script after selecting the `sales` database (or run the included `USE sales;` statement).
5. Review each result set.

## Notes

- The script is written for MySQL.
- The assignment's requested output columns are preserved in each query.
- Question 5 sorts by `buyPrice` but displays only `productName` and `quantityInStock`, as requested.
