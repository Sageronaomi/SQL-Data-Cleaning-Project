# SQL-Data-Cleaning-Project
Data Cleaning Project: Startup Layoffs Dataset

Overview

This project involves cleaning a dataset of startup layoffs as reported on https://www.kaggle.com/datasets/swaptr/layoffs-2022 since COVID-19 (March 11, 2020). The dataset contains information about companies, industries, number of layoffs, and other details.

The goal of this project is to ensure data quality by:

Removing duplicates

Standardizing data formats

Deleting unnecessary columns

Dataset

Source: https://www.kaggle.com/datasets/swaptr/layoffs-2022

Timeframe: March 11, 2020 – Present

Format: SQL database table

Data Cleaning Process

The SQL script performs the following tasks:

Remove duplicate entries to avoid redundancy.

Standardize text fields (e.g., company names, industry names, date formats).

Drop irrelevant columns that do not contribute to the analysis.

How to Run the SQL Script

Prerequisites

Ensure you have an SQL database system installed, such as:

MySQL

PostgreSQL

SQLite

Steps

Load the dataset into your SQL database.

Run the SQL script:

\\ Execute the script in your SQL environment
source Data_Cleaning_Project.sql;

Verify that duplicates are removed and data is standardized.

Expected Outcome

Cleaned dataset ready for analysis.

No duplicate records.

Consistently formatted data.

Unnecessary columns removed, improving dataset usability.

License

This project is for educational and analytical purposes. Feel free to use and modify the script.                                  
