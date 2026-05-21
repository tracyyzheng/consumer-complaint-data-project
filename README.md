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
# Dashboard Preview

## Complaints by Product
![Pie Chart](Pie%20Chart.png)

## Top Companies by Complaints
![Column Chart](Clustered%20Column%20Chart.png)

## Complaint Trends Over Time
![Line Chart](Line%20Chart.png)

## Consumer Complaint Heat Map by State
![Heat Map](Heat%20Map.png)

# Descriptive Analysis

The consumer complaint dataset revealed several important trends related to financial products and customer issues. Based on the dashboard visualizations, credit reporting and credit repair services generated the highest number of complaints among all product categories. This suggests that consumers experience more issues related to credit reports, incorrect information, and account disputes compared to other financial products.

The clustered column chart showed that a small number of financial companies accounted for a large portion of the complaints in the dataset. This indicates that complaint activity is concentrated among major financial institutions with larger customer bases.

The line chart demonstrated fluctuations in complaint volume over time. Complaint levels generally remained high across multiple years, showing that consumer financial issues continue to be a consistent concern.

The heat map visualization showed that states such as California, Florida, Texas, and New York had the largest concentration of complaints. These states also have larger populations and higher financial activity, which may contribute to the increased number of reported issues.

Overall, the dashboard helped identify patterns in consumer complaints, major product categories associated with disputes, and geographic areas with higher complaint activity. The visualizations made it easier to understand trends and summarize the data in a more meaningful way.

The dashboard was separated into multiple report pages to improve readability and organization.

# Key Findings

- Credit reporting related products generated the highest number of consumer complaints.
- Large financial institutions accounted for a significant portion of complaint volume.
- Complaint activity remained consistently high over multiple years.
- States such as California, Texas, Florida, and New York showed the largest concentration of complaints.
- Most complaints were submitted through web-based channels.

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
