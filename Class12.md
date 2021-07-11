# **Mongo and Mongoose**


# **nosql vs sql**

## **Fill in the chart below with five differences between SQL and NoSQL databases:**

|SQL|NoSQL|
|---|------|
relational| non-relational
structured query language and have a predefined schema|have dynamic schemas for unstructured data
vertically scalable|horizontally scalable
table based|document, key-value, graph or wide-column stores
better for multi-row transactions| better for unstructured data like documents or JSON

![img](https://phoenixnap.com/kb/wp-content/uploads/2021/04/database-types.jpg)

## **What kind of data is a good fit for an SQL database?**

### if your data is highly structured and associations among the program entities are clearly defined (for instance, if you are developing a point of sale system where you need to store customer orders and product records), conventional SQL based databases are the best fit.

## **Give a real world example.**

### **MySQL Community Edition**
### MySQL database is very popular open-source database. It is generally been stacked with apache and PHP, although it can be also stacked with nginx and server side javascripting using Node js.

## **What kind of data is a good fit a NoSQL database?**

###  to work better on both unstructured and unrelated data. The better solutions are the crossover databases that have elements of both NoSQL and SQL. RDBMSs that use SQL are schema–oriented which means the structure of the data should be known in advance to ensure that the data adheres to the schema

### **MongoDB**
### Mongodb is one of the most popular document based NoSQL database as it stores data in JSON like documents. It is non-relational database with dynamic schema. It has been developed by the founders of DoubleClick, written in C++ and is currently being used by some big companies like The New York Times, Craigslist, MTV Networks. 

## **Which type of database is best for hierarchical data storage?**

### Document based database like MongoDB, and Redis are great for small scale, hierarchical data with a relatively small amount of children for each entry


## **Which type of database is best for scalability?**
### in general, NoSQL/DDBMS will scale easier than RDBMS. In particular, ScyllaDB is the most scalable and one of the most performant NoSQL database that I currently know of, especially with respect to active/active regional DC replication , 
### First of all, MySQL, MSSQL, Oracle, PostgreSQL, all are highly scalable, it's just that they require little maintenance for it. All SQL based databases are very stable, and are in production since years.


## **What is a schema?**
### The term “schema” refers to the organization of data as a blueprint of how the database is constructed (divided into database tables in the case of relational databases). The formal definition of a database schema is a set of formulas (sentences) called integrity constraints imposed on a database.

![img](https://i.stack.imgur.com/68g6v.jpg)


## References:

* [nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)




