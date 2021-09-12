#

### SQL VS NOSQL

   SQL Database |  NOSQL Database
  -|-
  Relational Databases (RDBMS)|non-relational or distributed database.
  table based databases|document based, key-value pairs, graph databases or wide-column stores
  have predefined schema|have dynamic schema for unstructured data.
  uses SQL ( structured query language ) for defining and manipulating the data, which is very powerful.|queries are focused on collection of documents. Sometimes it is also called as UnQL (Unstructured Query Language).
  MySql, Oracle, Sqlite, Postgres and MS-SQL.|MongoDB, BigTable, Redis, RavenDb, Cassandra, Hbase, Neo4j and CouchDb
  SQL databases are good fit for the complex query intensive environment|not good fit for complex queries. On a high-level, NoSQL don’t have standard interfaces to perform complex queries,
  not best fit for hierarchical data storage.|database fits better for the hierarchical data storage as it follows the key-value pair way of storing data
  vertically scalable. You can manage increasing load by increasing the CPU, RAM, SSD, etc, on a single server.|horizontally scalable. You can just add few more servers easily in your NoSQL database infrastructure to handle the large traffic.
  best fit for heavy duty transactional type applications, as it is more stable and promises the atomicity as well as integrity of the data.|ou can use NoSQL for transactions purpose, it is still not comparable and sable enough in high load and for complex transactional applications.
   Excellent support are available for all SQL database from their vendors.|For some NoSQL database you still have to rely on community support, and only limited outside experts are available for you to setup and deploy your large scale NoSQL deployments.
  SQL databases emphasizes on ACID properties ( Atomicity, Consistency, Isolation and Durability)| the NoSQL database follows the Brewers CAP theorem ( Consistency, Availability and Partition tolerance )
  On a high-level, we can classify SQL databases as either open-source or close-sourced from commercial vendors.|NoSQL databases can be classified on the basis of way of storing data as graph databases, key-value store databases, document store databases, column store database and XML databases.

 ### What does SQL stand for?

 * structured query language(SQL)

### What is a realational database?

* type of database that stores and provides access to data points that are related to one another. Relational databases are based on the relational model

### What type of structure does a relational database work with?
* structure Database works with table

### What is a ‘schema’?

* it means that it have feilds and record forhese feilds

### What is a NoSQL database?

* NoSQL databases (aka "not only SQL") are non tabular, and store data differently than relational tables. NoSQL databases come in a variety of types based on their data model. The main types are document, key-value, wide-column, and graph. They provide flexible schemas and scale easily with large amounts of data and high user loads.

### How does it work?

*it works with collections and documents where you can use multiple documents in one collection .

### What is inside of a Mongo database?

* databases hold one or more collections of documents. To select a database to use,

### Which is more flexible - SQL or MongoDB? and why?
* NOSQL is more flexible because you can fill the documents you want from a collection and you can add more documents for some user to the collection and that something you can't use in schema in the SQL 

### What is the disadvantage of a NoSQL database?

*the duplicate data that you might have and you should update them in all of the collection they are in