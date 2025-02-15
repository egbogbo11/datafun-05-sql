# datafun-05-sql
## Make repository in Github and clone to local workspace
```bash
git clone https://github.com/egbogbo11/datafun-05-sql 
```

## Create .gitignore file
Ensure the following entries are added to your .gitignore file to exclude unnecessary files from being committed:

```bash
# Python virtual environment
.venv/

# Visual Studio Code settings and workspace
.vscode/

# Compiled Python files
__pycache__/

# Jupyter notebook checkpoints
.ipynb_checkpoints/
```

## Create and activate virtual environment

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the virtual environment:

```bash
.\.venv\Scripts\activate
```

## Create requirements.txt and download imports
Add the following libraries to your requirements.txt file:

```bash
pandas
pyarrow
```
## Create CSV files for authors and books

## Steps to complete Project 5
Step 1. Schema Design and Database Initialization

Design a schema with at least two related tables, including foreign key constraints. Document the schema design in your README.md.

sql_create folder:

01_drop_tables.sql - drop tables to restart

02_create_tables.sql - create your database schema using sql

03_insert_records.sql - insert at least 10 additional records into each table.
db01_setup.py:

Create a Python script that demonstrates the ability to create a database, define a schema, and insert records. Make it easy to re-run by dropping the tables first.

Step 2. Cleaning and Feature Engineering

Implement SQL statements and queries to perform additional operations and use Python to execute your SQL statements. You might create an additional table, insert new records, and perform data querying (with filters, sorting, and joining tables), data aggregation, and record update and deletion.

sql_features folder:

update_records.sql - update 1 or more records in a table.

delete_records.sql - delete 1 or more records from a table.

db02_features.py

Create a Python script that demonstrates the ability to run sql scripts to interact with fields, update records, delete records, and maybe add additional columns.

Step 3. Perform Aggregations and queries

Implement SQL statements and queries to perform aggregations and queries.

sql_queries folder:

query_aggregation.sql - use aggregation functions including COUNT, AVG, SUM.

query_filter.sql - use WHERE to filter data based on conditions.

query_sorting.sql - use ORDER BY to sort data.

query_group_by.sql - use GROUP BY clause (and optionally with aggregation)

query_join.sql - use INNER JOIN operation and optionally include LEFT JOIN, RIGHT JOIN, etc.

Use Python to execute the SQL queries and maybe chart, illustrate, and/or summarize your findings:

db03_queries.py