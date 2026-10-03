# Mini-SQL-Database-Engine
A Mini SQL Database Engine built using Flex and Bison in C. This project implements lexical analysis, SQL parsing, and an in-memory database system with support for CREATE TABLE, INSERT, SELECT, UPDATE, DELETE, WHERE conditions, LEFT/RIGHT JOIN, and aggregate functions such as COUNT, SUM, and AVG.
The project implements a custom SQL parser and an in-memory database system. It supports common SQL operations such as creating tables, inserting records, selecting data, updating records, deleting records, filtering with WHERE conditions, joins, and aggregate functions.

Features
CREATE DATABASE
CREATE TABLE
INSERT INTO
SELECT
UPDATE
DELETE
DROP TABLE
WHERE conditions with AND/OR
LEFT JOIN
RIGHT JOIN
COUNT()
SUM()
AVG()
Basic data types such as INT, VARCHAR, and FLOAT
In-memory table and row storage
SQL lexical analysis using Flex
SQL syntax parsing using Bison
Technologies Used
C
Flex / Lex
Bison / Yacc
GCC
Project Structure
db_lexer2.l — Lexical analyzer
db_parser2.y — SQL grammar and database engine
Generated parser files — created by Bison/Flex
Purpose

The main purpose of this project is to understand how lexical analysis, syntax parsing, and database operations can be combined to build a simple SQL processing system.
