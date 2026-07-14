World Layoffs SQL Data Cleaning

Project Overview

This project demonstrates a complete SQL data cleaning workflow using the World Layoffs dataset. The goal was to transform raw data into a clean, consistent, and analysis-ready dataset by applying SQL data cleaning techniques and best practices.

---

Project Objectives

- - Clean raw data for analysis
- - Remove duplicate records
- - Standardize inconsistent values
- - Handle missing (NULL) values
- - Convert data into appropriate formats
- - Improve overall data quality

- ---

Dataset Information

Dataset: World Layoffs

File: "world_layoffs.csv"

The dataset contains information about layoffs across companies, industries, countries, and years.

---

Tools Used

- MySQL
- - MySQL Workbench
- - SQL

- ---

SQL Skills Demonstrated

- CREATE TABLE
- - INSERT INTO
- - SELECT
- - UPDATE
- - DELETE
- - ALTER TABLE
- - Common Table Expressions (CTE)
- - ROW_NUMBER()
- - CASE Statements
- - TRIM()
- - REPLACE()
- - STR_TO_DATE()

- ---

Data Cleaning Steps

Step 1: Create a Staging Table

Created a duplicate table to preserve the original dataset.

Step 2: Remove Duplicate Records

Used "ROW_NUMBER()" to identify and remove duplicate rows.

Step 3: Standardize Data

- Cleaned company names
- - Standardized industry names
- - Standardized country names
- - Removed unnecessary spaces

- Step 4: Convert Date Format

- Converted date values into SQL "DATE" format.

- Step 5: Handle Missing Values

- - Filled missing values where possible
- - Removed records with insufficient information

- Step 6: Remove Unnecessary Columns

- Dropped helper columns that were no longer needed.

- Step 7: Validate the Dataset

- Verified the cleaned data for consistency and accuracy.

---

Skills Demonstrated

- - SQL Data Cleaning
- - Data Transformation
- - Data Validation
- - Data Standardization
- - NULL Value Handling
- - Common Table Expressions (CTEs)
- - Analytical Thinking
- - Database Management

----

Screenshots

Include screenshots of:

- - Original dataset
- - Duplicate removal
- - Data standardization
- - NULL value handling
- - Final cleaned dataset

----

Key Takeaways

This project strengthened my SQL skills by applying practical data cleaning techniques to prepare a real-world dataset for analysis.

---

Future Improvements

- - Automate the cleaning process
- - Create SQL Views
- - Build Stored Procedures
- - Connect the cleaned data to Power BI
- - Perform Exploratory Data Analysis (EDA)
