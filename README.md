# Jala_academy
JALA Academy: SQL and Python Learning Lab
This repository contains a comprehensive collection of fundamental exercises and solutions for SQL Database Management and Python Programming. The content is structured to cover everything from basic syntax to advanced concepts like subqueries in SQL and Object-Oriented Programming (OOP) in Python.

📁 Project Structure
sql_assignment.sql: A complete SQL script featuring database schema creation, data insertion, and 89 practical queries covering joins, aggregations, and subqueries.

jala_acedmy.py: A modular Python script demonstrating core programming concepts, including data types, file handling, exception management, and OOP.

📊 SQL Assignments
The SQL module uses a classic Salespeople-Customer-Orders schema. It covers:

Key Topics
Data Definition (DDL): Creating databases and tables with primary and foreign keys.

Data Manipulation (DML): Inserting records into salespeople, cust, and orders.

Basic Queries: Filtering with WHERE, IN, BETWEEN, and LIKE.

Aggregations: Using COUNT, SUM, AVG, MIN, MAX, and GROUP BY / HAVING.

Joins: Inner Joins, Self-Joins, and Union operations to combine data.

Subqueries: Correlated and non-correlated subqueries using EXISTS, ANY, and ALL.

Database Schema
Salespeople: snum (PK), sname, city, comm.

Customers: cnum (PK), cname, city, rating, snum (FK).

Orders: onum (PK), amt, odate, cnum (FK), snum (FK).

🐍 Python Programming Lab
The Python script is an educational walkthrough of the language's capabilities, following a structured learning path:

Modules Included
Basics: Variable scopes, data types (int, float, boolean), and printing techniques.

Operators: Arithmetic, relational, and logical operations.

Control Flow: while and for loops, including range-based logic.

Arrays & Collections: List manipulations, finding duplicates, and dictionary operations (nested dictionaries, key-value management).

OOP (Object-Oriented Programming):

Inheritance: Multilevel inheritance and method overriding.

Abstract Classes: Using the abc module to define interfaces.

Encapsulation: Private fields and access modifiers.

Constructors: Simulating multiple constructors using default arguments.

Exception Handling: try-except-finally blocks, handling ZeroDivisionError, and creating Custom Exceptions.

File I/O: Reading/writing text files, checking permissions, and using seek() for specific pointer placement.

🚀 How to Use
For SQL:
Copy the contents of sql_assignment.sql.

Run the script in any SQL environment (MySQL, PostgreSQL, etc.).

The script will automatically create the jalaacedmy database and populate it with data.

For Python:
Ensure you have Python 3.x installed.

Run the script via terminal:

Bash

python jala_acedmy.py
The script will execute various "Demos" showing output for packages, files, exceptions, and dictionaries.

🛠 Tech Stack
Database: SQL (MySQL compatible)

Language: Python 3.x

Library: math, re, os, abc
