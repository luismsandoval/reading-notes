# Data Modeling

## nosql vs sql

1. What type of database is the best fit for the complex query intensive environment?

   - A sql database. i.e. MySQL, MS-SQL, Oracle.

2. What type of database is the best fit for hierarchical data storage?

   - NoSQL databases fit better for hierarchical data storage because it uses key value pairs similar to JSON.

3. Describe the differences in scalability between a SQL and NoSQL database as though you were speaking to a non-technical friend.

   - SQL databases are vertically scalable, meaning you can increase load by increasing CPU, RAM, SSD, et cetera, on ONE server. NoSQL databases are horizontally scalable, meaning that you can add more servers on your database to handle more traffic.

## sql modeling techniques

1. Among data tables, what is a one-to-many relationship and how do we “relate” them?

   - When one model or table is related to many other tables. Relate them with a foreign key.

2. Prior to designing your relational database, it might be useful to **_ a _** of the database tables and their relationships.

   - **diagram**

3. Explain the difference between a primary and foreign key.

   - Primary keys id each row in a table, while foreign key is a key for a column or set of columns that mathc another tables foreign key.

## sql vs nosql

1. How do we treat keywords and parameters differently in SQL syntax?

   - We use the keywords and params to select entire columns instead of one key value pair.

2. Define normalization within the context of schemas and data.

   - The process to eliminate data redundancy, which helps organize the data in the database.

3. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

   - `one-to-one` refers to one table being directly related to another. Think _user table_ and _contact table_.

   - `one-to-many` refers to one table being connected to many tables. An example would be _user table_ being related to multiple _product tables_

   - `many-to-many` refers to multiple tables being connected to many other tables. For example, an _order table_ could be related to a _user table_ AND a _products table_.

## Sources

- [nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

- [sql modeling techniques](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)

- [sql vs nosql](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)
