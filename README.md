# Crowdfunding ETL Project

A collaborative project to build an ETL pipeline using Python, Pandas, and PostgreSQL for extracting, transforming, and loading crowdfunding data from Excel files into a relational database.

## Background

In this project, I practiced building an ETL pipeline to process crowdfunding data from Excel files. I extracted and transformed the data, created four CSV files, and then used the CSV files to create an Entity Relationship Diagram (ERD) and a table schema. Finally, I loaded the CSV files into a PostgreSQL database.

## Features

- Extract and transform crowdfunding and contact data from Excel files
- Create and export Category, Subcategory, Campaign, and Contact DataFrames as CSV files
- Design an ERD and table schema for the database
- Create and populate PostgreSQL database tables

## Installation

1. Clone the repository.
2. Install required Python packages: `pandas`, `openpyxl`, and `psycopg2`.
3. Set up a PostgreSQL server and create a new database called `crowdfunding_db`.

## Usage

1. Run the Jupyter Notebook to extract and transform data, and create CSV files.
2. Use the provided `crowdfunding_db_schema.sql` file to create tables in the PostgreSQL database.
3. Load the CSV files into the corresponding PostgreSQL tables.
4. Query the database to verify the data has been loaded correctly.

## Built With

- Python
- Pandas
- PostgreSQL
- Jupyter Notebook
- Excel

## License

This project is licensed under the MIT License.
