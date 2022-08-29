# MongoDB

**1. What is MongoDB ?**
Document base NoSQL database.
**2. What problem does it solve ?**
Store data without a schema, with replication, load balancing and speed.
**3. How does it differ from other NoSQL solutions ?**
- The document is the base.
- Data are stored in BSON (Binary JSON).
- Use JavaScript as the query language. 
**4. On which port does it listen ?**
`27017`
**5. What does mongosniff ?**
mongosniff is a tool to fetch live statistics of MongoDB.
**6. What is GridFS ?**
A distributed filesystem.
**7. What is a replica set ?**
A replica set is a group of MongoDB instances that contains the same data.
**8. What is sharding ?**
Sharding is a method for distributing data accross multiple machines.
**9. How do we monitor MongoDB ?**
Commands `mongostat` and `mongotop` allows to monitor MongoDB.
**10. What happen if MongoDB doesn't have enough memory ?**
It will start to use disk space, hence have a performance loss.