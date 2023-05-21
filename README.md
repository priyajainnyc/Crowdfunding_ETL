# crowdfunding_ETL
Project 2 for the ETL pipeline module of Datavis bootcamp

Title: The Art of Building an ETL Pipeline

Summary: Build an ETL pipeline using Python, Pandas and either Python dictionary methods or regular expressions to extract and transform the data. After you transform the data, create four CSV files and use the CSV file data to create an ERD and a table schema, and finally, upload the CSV file data into a Postgres database.

Guide Below: Imports, Resources, Files and PNGs 

Packages Imported: pandas as pd, numpy as np, pd.set_option('max_colwidth', 400), from datetime import datetime as dt, import json, import csv as dataframe 

Resources Used: Files called "crowdfunding.xlsx" and "contacts.xlsx" which contain the raw data

Notebooks Created: 

Python Notebook File With Full Code For All CSV Files Called: ETL_Mini_Project_Starter_Code.ipynb

CSV Files Produced From Notebooks and Subsequently Imported Into Postgres Located In "Resources" Folder Called: "campaign.csv", "category.csv", "contacts.csv", "subcategory.csv"

SQL File Exported from QuickDBD And Run In Postgres Called: "crowdfinding_db_schema.sql"

PNGs Created From: 
1. Screenshot of Crowdfunding Database ERD From QuickDBD Called: "crowdfunding_db_ERD.png"
2. Screenshots Of Tables Created In Postgres By Running CSV File Imports Using Schema Called: "campaign.png", "category.png", "contacts.png", "subcategory.png"