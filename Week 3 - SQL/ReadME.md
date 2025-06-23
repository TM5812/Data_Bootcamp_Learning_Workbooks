Week 3: Introduction to Databases and SQL Querying
Course Dates: 27th May – 30th May

🗂️ Overview
- Week 3 focused on understanding how databases work and developing hands-on SQL skills. 
- The week blended foundational theory with practical querying using a sample world database. 
- Explored relational database structures, wrote various SQL queries, and designed schemas for a retail business scenario.

🧠 Concepts & Skills Learned

Day 1: Database Foundations
Learned key relational database concepts:
- Primary keys vs Secondary keys
- Foreign keys and table relationships (1:1, 1:M, M:M)
- Explored real-world examples (e.g., passports, school mentors, courses)

Compared relational vs non-relational databases:
- Structured vs flexible data formats
- Best use cases for each (e.g., e-commerce, banking)

Day 3: SQL JOIN Types
- Studied various SQL JOIN operations with real-world use cases:

JOIN Type	Purpose
- INNER JOIN	Retrieves only matching rows from both tables
- LEFT JOIN	All records from left table + matched from right
- RIGHT JOIN	All records from right table + matched from left
- FULL JOIN	All records from both, matched or unmatched
- CROSS JOIN	Cartesian product of two tables
- SELF JOIN	Join a table to itself (e.g., employee-manager hierarchy)

Day 4: Retail Database Design
- Designed a relational database for a small retail business with a loyalty program:

Schema Design:
- Tables: Products, Customers, LoyaltyAccounts, Sales, SalesDetails
- Defined primary and foreign key relationships (1:1, 1:M)

SQL Implementation:
- CREATE DATABASE, CREATE TABLE, PRIMARY KEY, FOREIGN KEY
- Sample INSERT statements to populate data

Maintenance Plan:
- Use of TRIGGERS for automatic stock updates
- Backup strategy and role-based access for security

Day 4: SQL Practical (world_db)
- Completed practical SQL challenges using a sample world database:

Scenario	Query Focus
- Count cities in the USA =	COUNT()
- Find highest life expectancy = ORDER BY + LIMIT
- List cities with "New" in the name	= LIKE '%New%'
- Top 10 populous cities	= ORDER BY population DESC LIMIT 10
- Cities over 2 million population =	WHERE population > 2000000
- Cities starting with "Be"	= WHERE name LIKE 'Be%'
- Mid-size cities (500k–1M) =	BETWEEN
- Sort cities alphabetically	= ORDER BY name ASC
- Most and least populated cities	= Aggregate + sorting
- Capital cities, European cities	= Filtering by region/country/capital
- Average population by country =	GROUP BY + AVG()
- High GDP per capita cities	- Conditional filtering
- City name frequency	= GROUP BY name HAVING COUNT(*) > 1

💬 Reflections
- This week offered a deep dive into relational thinking, data modelling, and SQL logic.
- From theoretical concepts to real-life querying, the blend of design and practice supported the development of technical fluency with databases. 
- Building a database schema from scratch added valuable experience in structuring and translating business needs into scalable data models.

