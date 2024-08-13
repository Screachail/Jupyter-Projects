# SQL Data Analysis and Visualization

## Overview

This Jupyter Notebook demonstrates how to interact with an SQLite database, perform data cleaning, and visualize data using Python. The project involves creating a SQLite database, inserting data into tables, and using SQL queries to retrieve and manipulate the data. We also showcase how to visualize the data using a box plot to understand salary distributions across different departments.

## Project Components

1. **Database Creation and Data Insertion**:
    - Created SQLite tables: `departments` and `employees`.
    - Inserted sample data with some rows including missing values and duplicates.

2. **Data Cleaning**:
    - Used SQL queries to retrieve data with a `LEFT JOIN`.
    - Cleaned the data by removing rows with missing values.

3. **ACID Properties Demonstration**:
    - Illustrated Atomicity, Consistency, Isolation, and Durability using SQL transactions.

4. **Data Visualization**:
    - Created a box plot to visualize the distribution of salaries across different departments.

## Prerequisites

To run this notebook, you need the following packages:

- `sqlite3`
- `pandas`
- `seaborn`
- `matplotlib`
- `ipython-sql`
- `sqlalchemy`

You can install these packages using pip:

```bash
pip install sqlite3 pandas seaborn matplotlib ipython-sql sqlalchemy
