# Group Member: Juanita Sands and Simon Gomes

# Crowdfunding ETL Project

A collaborative project to build an ETL pipeline using Python, Pandas, and PostgreSQL for extracting, transforming, and loading crowdfunding data from Excel files into a relational database.

## Background

In this project, we engaged in practicing the construction of an ETL pipeline for the purpose of processing crowdfunding data derived from Excel files. The data was extracted and transformed, resulting in the creation of four CSV files. Subsequently, these CSV files were employed to generate an Entity Relationship Diagram (ERD) and a table schema. Lastly, we proceeded to load the CSV files into a PostgreSQL database.

## Features

- Extract and transform crowdfunding and contact data from Excel files
- Create and export Category, Subcategory, Campaign, and Contact DataFrames as CSV files
- Design an ERD and table schema for the database, we used https://www.quickdatabasediagrams.com/
- Create and populate PostgreSQL database tables, we used pgAdmin 4

## Installation

1. Clone the repository.
2. Install required Python packages: `pandas`, `numpy`, `datetime` and `json`.
3. Set up a PostgreSQL server and create a new database called `crowdfunding_db`.

## Usage

1. Run the [Jupyter Notebook](ETL_Mini_Project_SGomes_JSands.ipynb) to extract and transform data, and create CSV files.
2. Use the provided [sql](crowdfunding_db_schema_SGomes_JSands.sql) file to create tables in the PostgreSQL database.
3. Load the CSV files into the corresponding PostgreSQL tables. Ensure the CSV files are loaded in the order setout in the sql file.
4. Query the database to verify the data has been loaded correctly.

## Built With

- Python
- Pandas
- Json
- NumPy
- datetime
- PostgreSQL/PGAdmin
- Jupyter Notebook
- Excel
