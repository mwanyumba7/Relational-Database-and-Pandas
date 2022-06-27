# Relational Databases and Python

A database is a set of data that has been arranged and is structured to make it easier to save, retrieve, edit, and delete data. Relational databases and non-relational databases are the two basic categories of databases, with relational databases being the most common. The preferred language for interacting with relational databases is SQL, or Structured Query Language.


## Why Do Data Analysts Use Relational Databases & SQL?

SQL, or structured query language, is currently the most popular method of accessing data and databases. Numerous SQL functions make it simple for users to access, manipulate, and alter data. Additionally well-liked for data analysis is SQL since


- It's simple to comprehend and pick up.
- It can conduct queries on numerous tables at once, spanning big datasets, and can get data straight from where it is stored. It is also simple to audit and replicate.
- Compared to other analytical tools, it can provide more thorough and detailed answers to challenging topics.

Though Flat File structures such as CSV’s exist the disadvantages of this files include:

- Inadequate standards
- Redundancy in data
- Data sharing might be difficult
- Not appropriate for Large datasets 

A database's purpose is to serve as a repository for information that is needed by the majority of applications so that it can be accessed later. The language used to access this data by analysts and others is SQL.

Databases have a variety of benefits:


- They verify data integrity and ensure that data is entered in the right format.
- They can be tuned for performance and are quick over huge datasets.
- Since they are shared entities, numerous users can simultaneously access the same data.
- Access controls are among their administrative features.

Visit the following website to read a fantastic article on this subject: [Relational databases are not your father's flat files](https://www.cac.cornell.edu/education/Training/DataAnalysis/RelationalDatabases.pdf), says Cornell


## Information Storage in Relational Databases

Database tables will be familiar to you if you've used Excel. Tables have stricter standards than spreadsheets but are also made up of columns and rows.

Organizing database tables by column:


- Every column has a different name.
- A column's data must all be of the same data type.
- It's crucial to have descriptive column names.

**Types of SQL Statements**
The following fundamental SQL components are crucial to keep in mind:
A statement is a piece of properly written SQL code used to instruct a database on what to perform.


1. CREATE - builds a new database table.
2. The command "DROP TABLE" deletes a table from the database.
3. SELECT - often known as queries - lets you read and display data.

Important questions that each begin with two imperatives or command words:


- What data are you looking to pull FROM? Which data table do you wish to use?
- Which database elements do you wish to retrieve using the SELECT command? Which columns from that table do you wish to retrieve?

**Example**

    SELECT *
    FROM orders
    SELECT id, occurred_at
    FROM orders


## Data Wrangling and Relational Databases

It is advised that databases and SQL only be used for gathering or storing data in the context of data wrangling. Which is:

Establishing a connection to a database, bringing data into a pandas Data Frame (or the equivalent data structure in your choice programming language), analyzing and cleaning the data, or
establishing a connection to a database and storing the information you've just obtained, evaluated, and cleansed
When dealing with big amounts of data, these duties become even more crucial, which is where databases such as SQL and others outperform flat files.

The three primary tasks in the two above - mentioned scenarios are as follows:


- Python connection to a database
- Storing information from a pandas DataFrame in a linked database, and
- Importing information into a pandas DataFrame from a connected database

Here is a fascinating [Reddit post that compares and contrasts pandas and SQL](https://www.reddit.com/r/Python/comments/1tqjt4/why_do_you_use_pandas_instead_of_sql/) in general and touches on a number of data wrangling-related subjects.

## Practice Plan

In this repository I will be doing several projects on data wrangling and databases. To learn share and practice on the concept. 
Contributions are also welcomed to share progress, projects or ideas on Data Wrangling with databases  

