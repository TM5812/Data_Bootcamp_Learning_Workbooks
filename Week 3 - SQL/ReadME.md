# Week 3 – Introduction to Databases and SQL Querying  
📅 Course Dates: 27th May – 30th May 2025

## Overview

- This week introduced the fundamentals of database structures and SQL querying.
- Explored how relational databases operate, practised writing SQL commands, and designed a retail database schema that applied real-world business logic.

## 🗂️ Topics Covered

### 🏛️ Database Foundations (Day 1)
- Learned core relational concepts:
  - Primary Keys vs Secondary Keys  
  - Foreign Keys and table relationships:  
    - One-to-One (1:1)  
    - One-to-Many (1:M)  
    - Many-to-Many (M:M)  
- Real-world analogies:  
  - Passports (1:1), Mentors (1:M), Courses (M:M)  
- Compared relational vs non-relational databases:
  - Structured vs flexible data formats  
  - Use cases: banking, e-commerce, content storage  

### 🔗 SQL JOIN Types (Day 3)
Explored common SQL JOIN operations and their applications:

| JOIN Type   | Purpose                                               |
|-------------|--------------------------------------------------------|
| INNER JOIN  | Retrieves only matching rows from both tables          |
| LEFT JOIN   | All records from left table + matched from right       |
| RIGHT JOIN  | All records from right table + matched from left       |
| FULL JOIN   | All records from both tables, matched or unmatched     |
| CROSS JOIN  | Returns Cartesian product of two tables                |
| SELF JOIN   | Join a table to itself (e.g., employee-manager links)  |

### 🛒 Retail Database Design (Day 4)
Designed a scalable relational schema for a retail business with loyalty programs:

- **Schema Tables**:  
  - `Products`, `Customers`, `LoyaltyAccounts`, `Sales`, `SalesDetails`  
- **Relationships**:  
  - 1:1 (e.g., Customer → LoyaltyAccount)  
  - 1:M (e.g., Customer → Sales)  
- **SQL Implementation**:  
  - `CREATE DATABASE`, `CREATE TABLE`, `PRIMARY KEY`, `FOREIGN KEY`, `INSERT`  
- **Maintenance Plan**:  
  - Used `TRIGGERS` for stock updates  
  - Implemented role-based access and backups for security  

### 🧪 SQL Practical (world_db Dataset)
Practised real-world SQL challenges using a global cities dataset:

| Scenario                                 | SQL Concepts Used                        |
|------------------------------------------|------------------------------------------|
| Count US cities                          | `COUNT()`                                |
| Find highest life expectancy             | `ORDER BY` + `LIMIT`                     |
| Cities with “New” in the name            | `LIKE '%New%'`                           |
| Top 10 populous cities                   | `ORDER BY population DESC LIMIT 10`      |
| Cities over 2 million population         | `WHERE population > 2000000`             |
| Cities starting with “Be”               | `LIKE 'Be%'`                             |
| Mid-size cities (500k–1M)                | `BETWEEN`                                |
| Sort cities alphabetically               | `ORDER BY name ASC`                      |
| Most/least populated cities              | Aggregates + Sorting                     |
| Filter capital and European cities       | `WHERE` + `AND`                          |
| Average population by country            | `GROUP BY` + `AVG()`                     |
| High GDP per capita cities               | Conditional Filtering                    |
| City name frequency >1                   | `GROUP BY name HAVING COUNT(*) > 1`      |

## 🛠️ Tools & SQL Functions Practised

- `CREATE DATABASE`, `CREATE TABLE` – Define relational structure  
- `PRIMARY KEY`, `FOREIGN KEY` – Set relationships  
- `INSERT INTO` – Populate tables  
- `JOIN` types – Merge related data  
- `GROUP BY`, `HAVING`, `AVG`, `COUNT` – Aggregate data  
- `LIKE`, `BETWEEN`, `ORDER BY`, `LIMIT` – Filter and sort  

## ✅ Reflections

- Developed a strong foundation in database logic and structure  
- Practised applying SQL syntax to solve real-world questions  
- Built a relational schema from scratch, translating business needs into scalable table design  
- Gained confidence in using JOINs, filters, and aggregations for data analysis  
