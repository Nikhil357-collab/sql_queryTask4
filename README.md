# sql_queryTask4
# SQL Sorting & Pagination Practice

SQL practice project demonstrating ORDER BY, LIMIT, OFFSET, and index optimization for database interview preparation.

## Table of Contents

## Features
- Single and multi-column sorting (ASC/DESC)
- Pagination with LIMIT/OFFSET
- WHERE clause integration with ORDER BY
- Leaderboard ranking with RANK()
- Index optimization examples
- Edge case testing

## Database Schema

### Students Table (Original)
```sql
CREATE TABLE students (
    id INT PRIMARY KEY,
    name VARCHAR(50),
    class VARCHAR(10),
    marks INT
);
