# Cassandra

**1. What is Cassandra ?**
Distributed database system of NoSQL type.
**2. What problem does it solve ?**
Store large amount of data on multiple servers with no single point failure.
**3. How does it differ from other NoSQL solutions ?**
Distribution of data and reliability.
**4. How many nodes in a cluster does it require to keep up and running ?**
In depends on the replication factor.
The quorum is :
`(replication_factor / 2) + 1`
**5. What is CQL ? How does it differ from SQL ?**
*C*assandra *Q*uery *L*anguage
It is similar to SQL, but the organisation of the data differ, which reflect into the query language.
**6. What is the data model of Cassandra ?**
The Cassandra data model is a dynamic schema, column oriented data model.
**7. What is a columnar DB ?**
A database that store data in multiple columns.