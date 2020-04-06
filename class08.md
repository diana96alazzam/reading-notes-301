# Intro to SQL 
- **SQL**: **Structured Query Language**, is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database. And due to its simplicity, SQL databases provide safe and scalable storage for millions of websites and mobile applications.

- There are many popular SQL databases including: 
   * SQLite.
   * MySQL.
   * Postgres.
   * Oracle and Microsoft SQL Server.
- All of the above support the common SQL language standard, which is what this site (that I'm summarizing from) will be teaching, but each implementation can differ in the additional features and storage types it supports.

- **RELATIONAL DATABASES**
  - A relational database represents a collection of related (two-dimensional) tables. Each of the tables are similar to an Excel spreadsheet, with a fixed number of named columns (the attributes or properties of the table) and any number of rows of data.

- To retrieve data from a SQL database, we need to write **SELECT statements**, which are often colloquially refered to as **queries**.
- A **query** in itself is just : a statement which declares:
  * what data we are looking for.
  * where to find this data in the database.
  * and optionally, how to transform it before it is returned.

- If we want to selct multiple we write all of them sperated by a comma To Select query for all columns
    `SELECT * `
    `FROM mytable`
- In order to filter certain results from being returned, we use a WHERE clause in the query. The clause is applied to each row of data by checking specific column values to determine whether it should be included in the results or not.
  - Select query with constraints:
    `SELECT column, another_column, …`
    `FROM mytable`
    `WHERE condition`
    `AND/OR another_condition`
    `AND/OR …;`

- More complex clauses can be constructed by joining numerous AND or OR logical keywords. Below are some useful operators that you can use for numerical data (ie. integer or floating point):
![keywords](https://i.ibb.co/CKf4Yjw/read8.png)

- Writing clauses to constrain the set of rows returned benifits:
   1. Makes the results more manageable to understand.
   2. Allows the query to run faster due to the reduction in unnecessary data being returned.

- SQL doesn't require you to write the keywords all capitalized, but as a convention, it helps people distinguish SQL keywords from column and tables names, and makes the query easier to read.

- When writing WHERE clauses with columns containing text data, SQL supports a number of useful operators to do things like case-insensitive string comparison and wildcard pattern matching. We show a few common text-data specific operators below:
![text-data specific operators](https://i.ibb.co/MS80XHP/read8-1.png)

- All strings must be quoted so that the query parser can distinguish words in the string from SQL keywords.

- Full-text search is best left to dedicated libraries like Apache Lucene or Sphinx. These libraries are designed specifically to do full text search, and as a result are more efficient and can support a wider variety of search features including internationalization and advanced queries.

- SQL provides a convenient way to discard rows that have a duplicate column value by using the DISTINCT keyword because even though the data in a database may be unique, the results of any particular query may not be.

- Another clause which is commonly used with the **ORDER BY** clause are the **LIMIT** and **OFFSET** clauses, which are a useful optimization to indicate to the database the subset of the results you care about: 
   * The LIMIT will reduce the number of rows to return.
   * The optional OFFSET will specify where to begin counting the number rows from.






