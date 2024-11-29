# SQL Assignment Week 1


## *What You'll Need*
- A computer with internet access.
- A code editor (e.g., Visual Studio Code).
- MySQL Workbench or another SQL database environment.

---



## *Submission Instructions*
1. Answer every question below and put your responses in a file named `answers.md`
2. Push your completed `answers.md` file to your GitHub repository.
3. Submit the GitHub link for review.

---

## **Assignment Questions**

1. State and Explain the components of a DBMS(Database Management System)
Transaction Management:
Ensures that database transactions are executed reliably. It handles properties like ACID (Atomicity, Consistency, Isolation, and Durability).

Concurrency Control:
Manages multiple users accessing the database simultaneously, ensuring data consistency and preventing conflicts.

Data Security and Authorization:
Protects the database against unauthorized access and manages user permissions.

Data Dictionary:
Metadata repository that stores information about the database structure, including details about tables, columns, and relationships.

Backup and Recovery:
Provides tools for backing up data and restoring it in case of system failures or data corruption.


2. What is a relational database? Give 4 examples.
A relational database organizes data into tables (relations) with rows (records) and columns (fields). Relationships between tables are established using keys, ensuring data integrity and reducing redundancy.
3. State and Explain three classifications of SQL?
Data Definition Language (DDL):
Deals with the structure of the database.
Examples: CREATE, ALTER, DROP, TRUNCATE.

Explanation: Used to define or modify database schema (e.g., creating tables).
Data Manipulation Language (DML):
Handles data operations like retrieval, insertion, updating, and deletion.
Examples: SELECT, INSERT, UPDATE, DELETE.

Explanation: Used to manipulate the data stored in the database.
Data Control Language (DCL):
Manages access to the database.
Examples: GRANT, REVOKE.

Explanation: Ensures proper authorization and data security.
4. What is the difference between a Primary Key and a Foreign Key?

1. Components of a DBMS (Database Management System)
A DBMS is a software system used to create, manage, and interact with databases. Its primary components are:

Database Engine:
The core of the DBMS that handles data storage, retrieval, and manipulation. It ensures efficient data processing and enforces data integrity.

Database Schema:
The logical structure that defines how data is organized, including tables, fields, and their relationships.

Query Processor:
Interprets and executes database queries written in SQL or another query language. It translates user commands into operations the DBMS can perform.

Transaction Management:
Ensures that database transactions are executed reliably. It handles properties like ACID (Atomicity, Consistency, Isolation, and Durability).

Concurrency Control:
Manages multiple users accessing the database simultaneously, ensuring data consistency and preventing conflicts.

Data Security and Authorization:
Protects the database against unauthorized access and manages user permissions.

Data Dictionary:
Metadata repository that stores information about the database structure, including details about tables, columns, and relationships.

Backup and Recovery:
Provides tools for backing up data and restoring it in case of system failures or data corruption.

2. What is a Relational Database?
A relational database organizes data into tables (relations) with rows (records) and columns (fields). Relationships between tables are established using keys, ensuring data integrity and reducing redundancy.

Examples of Relational Databases:

MySQL
PostgreSQL
Oracle Database
Microsoft SQL Server
3. Classifications of SQL
SQL (Structured Query Language) commands are classified into three main categories:

Data Definition Language (DDL):
Deals with the structure of the database.
Examples: CREATE, ALTER, DROP, TRUNCATE.

Explanation: Used to define or modify database schema (e.g., creating tables).
Data Manipulation Language (DML):
Handles data operations like retrieval, insertion, updating, and deletion.
Examples: SELECT, INSERT, UPDATE, DELETE.

Explanation: Used to manipulate the data stored in the database.
Data Control Language (DCL):
Manages access to the database.
Examples: GRANT, REVOKE.

Explanation: Ensures proper authorization and data security.
Additional category:

Transaction Control Language (TCL):
Manages database transactions.
Examples: COMMIT, ROLLBACK, SAVEPOINT.
Explanation: Ensures transactions are processed correctly.
4. Difference Between a Primary Key and a Foreign Key
Feature	Primary Key	Foreign Key
Purpose	Uniquely identifies each record in a table.	Establishes a link between two tables.
Uniqueness	Must be unique and cannot contain null values.	Can contain duplicate and null values.
Location	Defined in the same table it resides in.	Refers to the primary key in another table.
Relationship	Represents the unique identifier of the table.	Enforces referential integrity by linking to a primary key.
5. What i. What is an Entity-Relationship Diagram?

1. What is an Entity-Relationship Diagram (ERD)?
An Entity-Relationship Diagram (ERD) is a graphical representation of the entities (data objects) in a database, their attributes, and the relationships between them. ERDs are used in database design to model the logical structure of a database.

Key components:

Entity: Represents a data object or table (e.g., "Student" or "Course").
Attribute: Properties or fields of an entity (e.g., "Name" or "ID").
Relationship: The association between entities (e.g., "Student enrolls in Course").
Cardinality: Indicates the number of instances in a relationship (e.g., one-to-many or many-to-many).
6. What are the advantages of relational databases?
Data Integrity: Ensures accuracy and consistency of data through constraints like primary and foreign keys.
Ease of Querying: Powerful query languages like SQL allow efficient data retrieval and manipulation.
Scalability: Relational databases handle large volumes of data and user transactions efficiently.
Data Relationships: Tables can be related, reducing data redundancy and improving organization.
Security: Role-based permissions and encryption protect sensitive data.
7. State four types of data type used to store data in tables?
   Numeric Data Types: Store numbers (e.g., INT, FLOAT, DECIMAL).
Character/String Data Types: Store text (e.g., CHAR, VARCHAR, TEXT).
Date and Time Data Types: Store date and time values (e.g., DATE, TIME, DATETIME).
Boolean Data Type: Stores true/false values (BOOLEAN or BIT).
8. What is the purpose of a database management system (DBMS

Data Storage and Retrieval: Ensures organized storage and quick access to data.
Data Security: Protects data from unauthorized access with user permissions and encryption.
Data Integrity: Maintains accuracy and consistency using constraints and validations.
Data Sharing: Allows multiple users and applications to access data concurrently.
Scalability: Supports growing amounts of data and users.
*How to edit a [markdownfile](https://www.markdownguide.org/basic-syntax/#headings)*

###  NOTE: You should not fork the repository
