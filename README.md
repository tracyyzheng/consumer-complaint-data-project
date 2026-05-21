# Consumer Complaint Data Pipeline Project

## Project Overview

This project focuses on analyzing consumer financial complaint data from the CFPB database. The goal of the project was to build a simple end-to-end data pipeline that includes data cleaning, cloud storage, dimensional modeling, and dashboard visualization.

The dataset contains information about customer complaints related to credit reporting, loans, debt collection, banking products, and other financial services. Using Python and Power BI, the raw data was transformed into a cleaner format that could be used for analysis and reporting.

---

# Tools Used

- Python
- Pandas
- Jupyter Notebook
- AWS S3
- Power BI

---

# ETL Process

The ETL process was completed in Jupyter Notebook using Python and Pandas.

Main transformations included:
- removing duplicate rows
- converting date columns into datetime format
- creating additional fields such as year, month, and quarter
- cleaning company names
- handling missing values in complaint narratives

The cleaned dataset was then exported as a CSV file for visualization and reporting purposes.

---

# Cloud Storage

AWS S3 was used to simulate cloud-based storage for the project.  
Files related to the raw data, transformed data, architecture diagrams, and documentation were uploaded into an S3 bucket.

Region used:
US East (Ohio)

---

# Data Warehouse Design

A dimensional model was created to organize the complaint data into fact and dimension tables. The project also includes:
- data mapping documentation
- data dictionary
- technical architecture
- information architecture diagrams

These files are included in the repository.

---

# Power BI Dashboard

The Power BI dashboard was created to visualize complaint trends and patterns in the dataset.

Visualizations included:
- complaints by product category
- top companies receiving complaints
- complaint trends over time
- complaint distribution by state
- interactive filtering by year

The dashboard was separated into multiple report pages to improve readability and organization.

---

# Repository Contents

This repository contains:
- ETL notebook
- cleaned dataset
- dimensional model
- architecture diagrams
- data mapping table
- data dictionary
- Power BI dashboard file

---

# Summary

This project demonstrates the process of building a basic analytics pipeline starting from raw data collection and ending with interactive business intelligence reporting. It combines data engineering concepts with visualization techniques to better understand trends in consumer financial complaints.
