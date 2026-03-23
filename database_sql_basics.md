# TryHackMe - Database SQL Basics

## Introduction

Databases are used to store, organize, and manage data efficiently.  
SQL (Structured Query Language) is the standard language used to interact with relational databases.

In cybersecurity, understanding SQL is important because many applications rely on databases, and vulnerabilities such as **SQL Injection** target them.

---

## What is a Database?

A database is a structured collection of data.

Relational databases store data in **tables**, which consist of:

- rows (records)
- columns (fields)

Example:

| id | name  | age |
|----|-------|-----|
| 1  | Alice | 25  |
| 2  | Bob   | 30  |

---

## What is SQL?

SQL (Structured Query Language) is used to:

- retrieve data
- insert data
- update data
- delete data

SQL allows users to interact with databases using queries.

---

## Basic SQL Commands

### SELECT

Used to retrieve data from a table.

```sql
SELECT * FROM users;
```

Select specific columns:

```sql
SELECT name, age FROM users;
```

---

### WHERE

Filters data based on conditions.

```sql
SELECT * FROM users WHERE age > 25;
```

---

### INSERT

Adds new data into a table.

```sql
INSERT INTO users (name, age) VALUES ('Alice', 25);
```

---

### UPDATE

Modifies existing data.

```sql
UPDATE users SET age = 26 WHERE name = 'Alice';
```

---

### DELETE

Removes data from a table.

```sql
DELETE FROM users WHERE name = 'Alice';
```

---

## Tables and Structure

A table is defined with columns and data types.

Example:

```sql
CREATE TABLE users (
    id INT,
    name VARCHAR(50),
    age INT
);
```

Each column has a specific type of data it can store.

---

## Primary Keys

A **primary key** uniquely identifies each row in a table.

Example:

```sql
id INT PRIMARY KEY
```

This ensures no duplicate values exist for that column.

---

## Why SQL Matters in Cybersecurity

SQL is important in cybersecurity because:

- most web applications use databases
- sensitive data is stored in databases
- attackers often target databases

One common attack is **SQL Injection**, where malicious SQL queries are used to manipulate the database.

Example of a vulnerable query:

```sql
SELECT * FROM users WHERE username = 'admin' AND password = '1234';
```

If not properly secured, attackers can inject code into input fields.

---

## Key Takeaways

- SQL is used to interact with relational databases.
- Databases store data in tables made of rows and columns.
- Common commands include SELECT, INSERT, UPDATE, and DELETE.
- Primary keys uniquely identify records.
- SQL knowledge is essential for understanding database-related vulnerabilities.

---

## Conclusion

The **Database SQL Basics** module introduces how databases work and how to interact with them using SQL.

Understanding SQL is essential for both developers and cybersecurity professionals, especially when dealing with data security and vulnerabilities.