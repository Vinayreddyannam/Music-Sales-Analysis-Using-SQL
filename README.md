# Music-Sales-Analysis-Using-SQL
Music Store Database Management System built using MySQL. This project includes database design, table creation with relationships, and advanced SQL queries such as JOINs, GROUP BY, subqueries, and window functions to analyze customer spending, top genres, artist popularity, and sales insights.
# Music Store Database Management System

## Project Overview
The Music Store Database Management System is a SQL-based project developed using MySQL.  
It simulates a digital music store where customers purchase tracks, artists release albums, and invoices track sales transactions.

This project demonstrates database design, table relationships, and advanced SQL queries for business analysis.
## Database Name
music_store
## Database Schema

The project contains the following tables:

1. Genre  
2. MediaType  
3. Employee  
4. Customer  
5. Artist  
6. Album  
7. Track  
8. Invoice  
9. InvoiceLine  
10. Playlist  
11. PlaylistTrack  

All tables are connected using Primary Keys and Foreign Keys to maintain relational integrity.

## Key Features

- Database and table creation using DDL commands
- Implementation of Primary and Foreign Key constraints
- Complex JOIN operations across multiple tables
- Aggregation using GROUP BY
- Subqueries for analytical queries
- Window functions (RANK) for ranking results
- Business insight queries for customer and sales analysis

## Business Questions Solved

The project answers important analytical questions such as:

- Who is the senior-most employee?
- Which country generates the most invoices?
- What are the top 3 highest invoice totals?
- Which city generates the highest revenue?
- Who is the best customer based on spending?
- List of Rock music listeners.
- Top 10 Rock artists based on track count.
- Tracks longer than average duration.
- Amount spent by each customer on each artist.
- Most popular genre per country.
- Top spending customer per country.

## SQL Concepts Used

- CREATE DATABASE
- CREATE TABLE
- PRIMARY KEY
- FOREIGN KEY
- JOIN (INNER JOIN)
- GROUP BY
- ORDER BY
- LIMIT
- Subqueries
- Common Table Expressions (CTE)
- Window Functions (RANK())

## Tools Used
- MySQL
- MySQL Workbench
## How to Run the Project
1. Install MySQL.
2. Open MySQL Workbench.
3. Create a new SQL file.
4. Copy and paste the provided SQL script.
5. Execute the script.
6. Run analytical queries to generate insights.
## Learning Outcomes
- Understanding relational database design
- Writing optimized SQL queries
- Performing data analysis using SQL
- Using window functions and CTEs
- Generating business insights from raw data
## Author
Vinay Reddy
## Conclusion
This project demonstrates strong SQL fundamentals, database design skills, and the ability to solve real-world business problems using structured query language.
