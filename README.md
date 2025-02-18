# Relational Database Management Systems (RDBMS)

This document provides an overview of three well-known Relational Database Management Systems (RDBMS): **MySQL**, **PostgreSQL**, and **SQL Server**. It also includes a detailed comparison of their functionalities, use cases, and ecosystems.

---

## Definition of RDBMS

**RDBMS** stands for **Relational Database Management System**, which is designed specifically for relational databases. A database is relational if it stores data in a structured format, using rows and columns. This structure makes it easy to locate and access specific values within the database. The term "relational" refers to the relationships between values within each table, as well as the relationships between tables.

The most well-known RDBMS are:
- **MySQL** ![MySQL Icon](https://img.icons8.com/color/48/000000/mysql-logo.png)
- **PostgreSQL** ![PostgreSQL Icon](https://img.icons8.com/color/48/000000/postgreesql.png)
- **Microsoft SQL Server** ![SQL Server Icon](https://img.icons8.com/color/48/000000/microsoft-sql-server.png)

---

## MySQL ![MySQL Icon](https://img.icons8.com/color/48/000000/mysql-logo.png)

MySQL, pronounced either "My S-Q-L" or "My Sequel," is an open-source RDBMS based on the Structured Query Language (SQL). It is used for adding, removing, and modifying information in the database. MySQL is commonly found on web servers and is often used in dynamic web pages that access information from a database.

- **License**: Open-source and free under the GNU license.
- **Supported by**: Oracle.
- **Icon**: ![MySQL Icon](https://img.icons8.com/color/48/000000/mysql-logo.png)

---

## PostgreSQL ![PostgreSQL Icon](https://img.icons8.com/color/48/000000/postgreesql.png)

PostgreSQL is an advanced open-source RDBMS known for its robustness and extensibility. It supports transactions with **ACID** properties (Atomicity, Consistency, Isolation, Durability) and is designed to handle a wide range of workloads, from single machines to large data warehouses or web services with many concurrent users.

- **Features**:
  - Supports custom data types and functions.
  - Allows writing code in different programming languages without recompiling the database.
  - Highly extensible and suitable for both small and large datasets.
- **Icon**: ![PostgreSQL Icon](https://img.icons8.com/color/48/000000/postgreesql.png)

---

## SQL Server ![SQL Server Icon](https://img.icons8.com/color/48/000000/microsoft-sql-server.png)

SQL Server is a RDBMS developed by Microsoft. It serves as a central location for storing and retrieving data needed for applications. SQL Server uses SQL for queries and supports user-defined composite types (UDTs). It also provides server statistics through Dynamic Management Views (DMVs).

- **Features**:
  - Supports tables, views, stored procedures, indexes, and constraints.
  - Includes a transaction log for data integrity.
- **Icon**: ![SQL Server Icon](https://img.icons8.com/color/48/000000/microsoft-sql-server.png)

---

## Comparison Between MySQL, PostgreSQL, and SQL Server

Below is a detailed comparison of the three RDBMS based on various criteria:

| **Criteria**         | **MySQL** ![MySQL Icon](https://img.icons8.com/color/48/000000/mysql-logo.png)                                                                 | **PostgreSQL** ![PostgreSQL Icon](https://img.icons8.com/color/48/000000/postgreesql.png)                                                                 | **SQL Server** ![SQL Server Icon](https://img.icons8.com/color/48/000000/microsoft-sql-server.png)                                                                 |
|-----------------------|---------------------------------------------------------------------------|--------------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| **Price**            | Core functionality is free; additional paid tools available.              | Open-source.                                                                   | Free edition for developers and small businesses (limited to 1 processor and 1GB memory). |
| **Language**         | C++                                                                      | C                                                                              | C++                                                                            |
| **Used by Companies**| Google, Udemy, Netflix, Airbnb, Amazon                                   | Apple, Skype, Cisco                                                            | Bank of America, UPS                                                           |
| **Partitioning**     | Allows partitioning with hashing functions.                               | Supports LIST and RANGE partitions.                                            | Provides RANGE partitioning.                                                   |
| **Defragmentation**  | Offers multiple approaches (backup, index creation, OPTIMIZE Table).     | Scans entire tables to find and delete empty rows.                             | Efficient garbage collector with low overhead.                                 |
| **JSON Support**     | Supports JSON but no indexing.                                            | Supports JSON, including indexing and partial updates.                         | Full support for JSON documents.                                               |
| **Data Queries**     | Scalable buffer pool with customizable cache size.                        | Isolates processes further by treating them as separate OS processes.          | Uses a buffer pool with adjustable size.                                       |
| **Indexes**          | Organized indexes in tables and clusters; automatic index updates.        | Supports index-based table organization; early versions lack automatic updates.| Rich automated functionality for index management.                             |
| **Temporary Tables** | Limited functionality; no variables or global templates.                 | Flexible temporary tables with local and global options.                       | Rich functionality for temporary tables and variables.                          |

---

## Conclusion

The choice between **MySQL** ![MySQL Icon](https://img.icons8.com/color/48/000000/mysql-logo.png), **PostgreSQL** ![PostgreSQL Icon](https://img.icons8.com/color/48/000000/postgreesql.png), and **SQL Server** ![SQL Server Icon](https://img.icons8.com/color/48/000000/microsoft-sql-server.png) ultimately depends on the specific needs of the user or organization. Companies that prioritize flexibility, cost-efficiency, and innovation often opt for open-source solutions like MySQL and PostgreSQL. These systems can be integrated with multiple free add-ons, have active user communities, and are continuously updated. On the other hand, SQL Server is a robust option for enterprises that require advanced features and are willing to invest in a commercial solution.

---

**Author**: Bado Idriss Olivier
