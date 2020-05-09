# Day 1

# POSTGRESQL

* `CREATE DATABASE` to create the database

* `\c` to connect to database.

* Every `JOIN` must have an `ON`

* `HAVING` is for aggregate data, `WHERE` is for indivdual data.

* `FROM` is useful to create a table to query from.

* The `UNION` operator does what you might expect: combines the results of two SQL queries into a single table. The caveat is that both results from the two queries must have the same number of columns and compatible data types.

* `UNION` removes duplicate rows, while UNION ALL does not. Use UNION ALL by default, unless you care about duplicate results.

* You can `JOIN` a table to itself to get overlapping information.

# Lecture Notes

* columns = fields (adjectives or Keys if object);

* rows = records (1 row for each entity)

* do not misuse `SELECT *` be specific

* use single quotes for strings in SQL. Double quotes are for table names etc.

* add more to ORDER BY with a `,`.

* `LEFT JOIN` joins all matches plus the left table records

* `RIGHT JOIN` joins all matches plus the right table records

