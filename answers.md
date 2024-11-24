# Answers

### 1. What are the components of a DBMS?
1. **Database Engine**: Manages data storage and retrieval.
2. **Schema**: Defines database structure.
3. **Query Processor**: Executes and optimizes queries.
4. **Transaction Manager**: Ensures ACID properties.
5. **Storage Manager**: Handles physical data storage.
6. **Metadata Manager**: Manages database metadata.
7. **Concurrency Control Manager**: Handles simultaneous access.
8. **Recovery Manager**: Recovers data after failures.
9. **User Interface**: Enables interaction with the database.
10. **Security Manager**: Controls data access and security.

---

### 2. What is a relational database? Give 4 examples.
A relational database organizes data into tables (relations) with rows and columns, using keys to establish relationships between tables.  

Examples:  
1. MySQL  
2. PostgreSQL  
3. Microsoft SQL Server  
4. Oracle Database  

---

### 3. State and Explain three classifications of SQL.
1. **DDL (Data Definition Language)**: Manages database structure (e.g., `CREATE`, `ALTER`, `DROP`).  
2. **DML (Data Manipulation Language)**: Manipulates table data (e.g., `SELECT`, `INSERT`, `UPDATE`, `DELETE`).  
3. **DCL (Data Control Language)**: Manages access control (e.g., `GRANT`, `REVOKE`).  

---

### 4. What is the difference between a Primary Key and a Foreign Key?
- **Primary Key**: Ensures unique identification of records; cannot be `NULL`.  
- **Foreign Key**: Links tables by referencing a primary key; can contain `NULL`.  

---

### 5. What is an Entity-Relationship Diagram (ERD)?
An ERD is a visual tool that represents a database's structure, showing entities (tables), attributes (columns), and their relationships.

---

### 6. What are the advantages of relational databases?
1. **Data Integrity**: Ensures consistency and accuracy.  
2. **Flexibility**: Manages complex queries and relationships.  
3. **Scalability**: Handles large datasets efficiently.  
4. **Security**: Restricts access with roles and permissions.  

---

### 7. State four types of data type used to store data in tables.
1. **INTEGER**: Stores whole numbers.  
2. **VARCHAR**: Stores variable-length text.  
3. **DATE**: Stores date values (`YYYY-MM-DD`).  
4. **FLOAT**: Stores decimal numbers.  

---

### 8. What is the purpose of a DBMS?
A DBMS stores, retrieves, and manages data efficiently while ensuring data integrity, security, and multi-user access.
