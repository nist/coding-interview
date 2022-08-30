# PostgreSQL

**1. What is PostgreSQL ?**
PostgreSQL is an *O*bject *R*elational *D*ata*B*ase *M*anagement *S*ystem.
It is based on POSTGRES, a database developed at Berkeley.
**2. How it differ from MySQL ?**
PostgreSQL got only one storage engine and have many features that MySQL doesn't have.
**3. What are roles ?**
The method to handle privileges for users.
**4. How to backup a database ?**
With the tool `pg_dump`.
**5. How to monitor the database server ?**
The standard Unix tools can be used.
PostgreSQL also keep statistics which can be useful.
Otherwise, there's different applications that can be used to monitor the server.
**6. How to get current date and time in PostgreSQL ?**
`SELECT CURRENT_DATE;`
**7. How to split a big table in multiple tables ?**
With a partition. Each table will contain a range of data.
**8. What does a trigger ?**
It execute code when a specific event occur.
**9. What is needed to update stastistics ?**
The command `ANALYZE`.
**10. What is a tablespace ?**
Allow DBA to specify where to store the database in the filesystem.