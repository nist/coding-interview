# MySQL

**1. What is MySQL ?**
It's an open source RDBMS.
**2. Who owns it ?**
Oracle
**3. What difference between MySQL and MariaDB ?**
When Oracle acquire Sun, the previous owner of MySQL, the community was afraid that Oracle would close MySQL. Hence a fork was created, MariaDB. Since then both evolved separately, but keep a compatibility.

MySQL and MariaDB support different storage engines and have different set of features.   
**4. How to get current date/time in MySQL ?**
`SELECT curdate();`
**5. How to enforce strict SQL in MySQL ?**
On InnoDB :
`SET @@global.innodb_strict_mode = ON;`
**6. How to get current date and time in MySQL ?**
**7. How to know the value of a global variable in MySQL ?**
`SHOW GLOBAL VARIABLES;`
**8. What does the command `SHOW STATUS` ?**
It provides server status information.
**9. Name some storage engines for MySQL and their features.**
MyISAM : Fast and simple.
InnoDB : Enforce 3rd form normalization, like foreign keys and transactions.
Otherwise, see `SELECT ENGINE, SUPPORT FROM information_schema.ENGINES;` for a list of engine and their support.
**10. How to import CSV data in a table ?** 
With the command `LOAD DATA INFILE`.