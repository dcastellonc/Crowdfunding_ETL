# Crowdfunding_ETL
Pair 17- Brian Omirera and Daniela Castellon
Instructions
The instructions for this mini project are divided into the following subsections:
- Create the Category and Subcategory DataFrames
- Create the Campaign DataFrame
- Create the Contacts DataFrame
- Create the Crowdfunding Database


Create the Category and Subcategory DataFrames
Extract and transform the crowdfunding.xlsx . Export the category DataFrame as category.csv  and the subcategory DataFrame as subcategory.csv and save it to your GitHub repository.

Export the campaign DataFrame as campaign.csv and save it to your GitHub repository.
Create the Contacts DataFrame
Choose one of the following two options for extracting and transforming the data from the contacts.xlsx Excel data:
Option 1: Use Python dictionary methods.
Option 2: Use regular expressions.


Create the Crowdfunding Database
- Inspect the four CSV files, and then sketch an ERD of the tables by using QuickDBD
Use the information from the ERD to create a table schema for each CSV file.
Note: Remember to specify the data types, primary keys, foreign keys, and other constraints.
- Save the database schema as a Postgres file named crowdfunding_db_schema.sql, and save it to your GitHub repository.
- Create a new Postgres database, named crowdfunding_db.
- Using the database schema, create the tables in the correct order to handle the foreign keys.
- Verify the table creation by running a SELECT statement for each table.
- Import each CSV file into its corresponding SQL table.
Verify that each table has the correct data by running a SELECT statement for each.
