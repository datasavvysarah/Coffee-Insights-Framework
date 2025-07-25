# Coffee_sqldatabse_query

Coffee Database Management System
A comprehensive SQL database system for managing coffee shop operations, including shops, employees, locations, and suppliers.

## Database Structure Overview

This database consists of four main tables designed to handle coffee shop operations:

Shop: Core coffee shop information

Employee: Staff management and details

Location: Geographic and address information

Suppliers: Vendor and supply chain management

## Entity Relationship:

- Each shop has multiple employees (1:N relationship)
- Each shop is located at one location (1:1 relationship)
- Each shop can work with multiple suppliers (N:M relationship through shop_suppliers junction table)

## Database Schema
Table Definitions
1. Location Table: Stores address and geographic information for coffee shops.
2. Shop Table: Table containing coffee shop information and business details.
3. Employee Table: Stores employee information with relationship to their assigned shop.
4. Suppliers Table: Manages supplier information and contact details.

## Project Files Structure

This database project contains separate SQL files for different components:

create-insert.sql: Contains all CREATE TABLE and INSERT statements for the database schema

query and subqueries.sql: Contains useful SELECT queries and subqueries for data analysis and reporting

## Installation and Setup

Prerequisites: MySQL or PGAdmin

## Database Creation:

1. CREATE DATABASE coffee_db;
2. USE coffee_db;

- Execute SQL files in the following order:
- Run create-insert.sql to create the database structure and populate with the sample data
- Use query and subqueries.sql for data analysis and reporting


