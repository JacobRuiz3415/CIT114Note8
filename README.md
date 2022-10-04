# CIT114Note8
## Main points
- A database is a collection of related data.
- Its purpose organizing sets of data to make them useful 
- fundamental concepts of databases includes fields, records, tables, and relationships.
- This data is stored as a record, and each aspect is stored in a field.
- Each field uses a data type for that data, such as Short text or number.
- A Table is an object that displays all records of a data set.
- The primary key is a field that has a value unique in all records.
- A primary key is used to connect a primary table to a related table.
- A database management system is an application to create and maintain databases.
- A database system is a self-described system.
- In which the database contains the metadata that defines the data relationship and data structure. 
- This creates a separation between metadata and data itself.
- There is also data-program independence, as metadata is stored in the system, not the program.
- Modern data systems are designed for multi-user access, or multiple users can access the same database.
- Also, the database can be shared with these many users.
- A database system has integrity constraints to make sure users enter valid information in the database.
- A query is a request on how data is process.
- A query can calculates a certain field, compares data from different tables, or restricts data by a criteria.
- There are four basic commands for an SQL database, CREATE, SELECT, UPDATE, and DELETE.
- Cloud database service can be managed or unmanaged.
- Unmanaged means that the management and data maintenance by done by you
- Managed database means data maintenance is managed by the service provider.
- Amazon RDS is a cloud-based managed Relational database
- A DB instance is an isolated database environment hosted in the AWS cloud.
- A DB instance can be run in the VPC, and it can work with EC2 instances.
- Amazon dynamic DB is a cloud-based NoSQL database.
- NoSQL or nonrelational databases are a type of system that does not use the same data structures as other databases.
- NoSQL means the database does not use the SQL quarry language.
- Benefits of NoSQL are flexibly and scalability.
## Quote
- “When you run your own database server, you are responsible for several administrative tasks, such as server maintenance and energy footprint, software, installation and patching, and database backups. You are also responsible for ensuring high availability, planning for scalability, data security, and operating system (OS) installation and patching. All these tasks take resources from other items on your to-do list and require expertise in several areas.”
- “Companies in the gaming vertical use DynamoDB in all capabilities of game platforms, including game state, player data, session history, and leaderboards. The main benefits that these companies get from DynamoDB are its ability to scale reliably to millions of concurrent users and requests while ensuring consistently low latency measured in single-digit milliseconds.”
## New facts
- When updating data in SQL, you need to add where and what record you want to update, or you might corrupt your database. 
- Also, remember to do the same when deleting a record, or you might ruin your database.
-In Amazon RDS, you choose from current DB engines, such as Aurora, MySQL, MariaDB, Oracle, Microsoft SQL Server, and PostgreSQL.
NoSQL is becoming more popular.
