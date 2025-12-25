\# ETL Banks Project



\## Overview

This project implements an automated ETL (Extract, Transform, Load) pipeline that compiles

a quarterly report of the \*\*top 10 largest banks in the world by market capitalization\*\*.



The pipeline extracts data from an archived Wikipedia source, transforms market

capitalization values into multiple currencies, and loads the processed data into

both CSV and SQLite database formats.



\## Data Sources

\- \*\*Bank data:\*\* Wikipedia (archived snapshot)

\- \*\*Exchange rates:\*\* CSV file provided by IBM Skills Network



\## ETL Pipeline



\### Extract

\- Scrapes the \*\*By market capitalization\*\* table

\- Extracts bank name and market capitalization in USD



\### Transform

\- Converts USD values into GBP, EUR, and INR

\- Rounds values to 2 decimal places



\### Load

\- Saves results to a local CSV file

\- Loads data into a SQLite database table



\### Query \& Validation

\- Executes SQL queries to validate transformed data

\- Computes aggregate statistics



\### Logging

\- Logs progress at each ETL stage for traceability



\## Technologies Used

\- Python

\- Pandas

\- BeautifulSoup

\- SQLite

\- NumPy

\- Requests



\## Author

Abdelkabir Sahnoun



