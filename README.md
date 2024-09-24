# Crowdfunding_ETL
## UNCC Data Science Bootcamp - Module 13 Project 2

The object of this mini project was to build an ETL pipeline using Python, Pandas, and either Python dictionary 
or regular expressions to extract and transform data.
For this purpose, the crowdfunding.xlsx and contacts.xlsx files were used as the source data.

The data in these two files was transformed and the following CSV files were created:
category.csv
subcategory.csv
contacts.csv
campaign.csv

The CSV files were used to create a database using QuickDBD to generate the ERD and used as input for
Postgres SQL:
QuickDBD-Crowdfunding_db (2).sql - QuickDBD output file
QuickDBD-Crowdfunding_db_final.sql - VScode revised file
crowdfunding_db_schema.sql - Postgres SQL resulting file

All the above files can be found in the "Resources" folder.

ERD files and images from both QuickDBD and Postgres SQL can be found in the "Resources\ERD" folder.
Verification of the different tables created are shown with captured images saved as PNG files and
can be found in the "Resources\Query Images" folder.
