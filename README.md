# DBMS Exam Preparation - Library Management System

This repository contains the foundational database setup for a **Library Management System**, designed to jumpstart your preparation for DBMS exams.

## What is Included?
To save you time and effort during your revision, **this repository strictly contains the code for table creation (DDL) and value insertion (DML)**. 

Writing repetitive `CREATE TABLE` and `INSERT INTO` commands from scratch is tedious and time-consuming. This sample is provided to handle that boilerplate setup for you, giving you an instant, populated sandbox database.

## Your Task: Practice & Study
The rest of the core DBMS concepts are meant for **you to practice and study on your own**. With the foundational data already live and connected, you can focus 100% of your energy on writing, testing, and mastering exam-heavy topics like:
* **Aggregate Functions & Grouping** (`COUNT`, `SUM`, `GROUP BY`, `HAVING`)
* **Relational Joins** (`INNER`, `LEFT`, `RIGHT`, and `SELF JOIN`)
* **Subqueries** (Nested, Correlated, and Subqueries in `FROM`/`WHERE` clauses)
* **Database Objects** (Creating your own Views, Triggers, and Stored Procedures)

## Quick Setup
Run this single command in your terminal to spin up your practice playground after cloning this repo:
```
git clone https://github.com/MabelMoncy/DBMS-EXam-Preparation
```
```
cd DBMS-EXam-Preparation
```
```
mysql -u root -p
Enter password:
```
```
CREATE DATABASE IF NOT EXISTS LIBRARY_MANAGEMENT;
USE LIBRARY_MANAGEMENT;
```
```
SOURCE queries.sql;
```
```
mysql -u root -p < queries.sql
```
