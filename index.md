---
layout: home
title: NYC 311 Complaints Data
---

# 🗽 NYC 311 Complaints Data with MySQL & Python

This project demonstrates how to:

- Connect to a MySQL database
- Create a new database and table
- Fetch NYC 311 complaint data via the [NYC Open Data API](https://data.cityofnewyork.us/)
- Insert the data into your MySQL database using Python

## 🐍 Python Script Overview

The Python scripts include:

1. **Database Initialization**:
   - Connects to MySQL
   - Creates a database (`open_data_NYC`)
   - Creates a table (`311_complaints`) with proper schema

2. **Data Ingestion**:
   - Uses NYC's 311 complaints API (`erm2-nwe9`)
   - Fetches data for 2024 in batches
   - Inserts cleaned, flattened data into the table

> The year of data (`2024`) can be adjusted as needed — simply modify the date filters in the script.  
> This project can serve as a template for creating tables and fetching data from **any** dataset available on the NYC Open Data platform using the API.

You can view or clone the code from the repository and run the Python script locally.

---

## 🧩 Dependencies

Install required Python packages:

```bash
pip install mysql-connector-python requests
