# layoffs-data-cleaning-project
Cleaned a real-world layoffs dataset using SQL by removing duplicates, handling missing values, standardizing records, and preparing data for analysis.



# SQL Data Cleaning Project - Layoffs Dataset

## Overview

This project demonstrates data cleaning techniques using SQL on a real-world layoffs dataset.

The dataset contained duplicate records, missing values, inconsistent text formats, and incorrect date formats.

The goal was to prepare the dataset for further analysis by improving data quality and consistency.

---

## Tools Used

- SQL
- MySQL

---

## Skills Demonstrated

- Data Cleaning
- Window Functions
- ROW_NUMBER()
- Common Table Expressions (CTEs)
- Self Joins
- NULL Handling
- Date Conversion
- Data Standardization

---

## Data Cleaning Process

### 1. Remove Duplicates

Used ROW_NUMBER() to identify and remove duplicate records.

### 2. Standardize Data

- Trimmed company names
- Standardized industry names
- Cleaned country values
- Converted date format

### 3. Handle Missing Values

- Replaced blank values with NULL
- Filled missing industries using self joins

### 4. Remove Unnecessary Records

Deleted rows where layoff information was completely missing.

### 5. Final Cleanup

Removed helper columns used during the cleaning process.

---

## Project Screenshots

### Raw Dataset

![Raw Dataset](screenshots/raw_dataset.png)

### Duplicate Detection

![Duplicate Detection](screenshots/duplicate_detection.png)

### NULL Handling

![NULL Handling](screenshots/null_handling.png)

### Final Cleaned Dataset

![Final Dataset](screenshots/final_cleaned_dataset.png)

---

## SQL File

The complete SQL script is available in:

Data_Cleaning.sql

---

## Author

Amrit Mishra
