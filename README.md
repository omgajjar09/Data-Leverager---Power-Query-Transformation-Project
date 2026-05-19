# Data Leverager – Power Query Transformation Project

## Project Overview
This project demonstrates advanced data transformation, cleaning, and preparation techniques using **Microsoft Power BI** and **Power Query Editor**. The goal of this project is to import data from multiple sources, clean and transform the data, create calculated columns, perform data profiling, and prepare the dataset for reporting and dashboard analysis.

The project focuses on practical business scenarios such as sales analysis, employee data management, and data standardization.

---

# Tools & Technologies
- Microsoft Power BI
- Power Query Editor
- DAX (Basic Calculations)
- Data Transformation Techniques
- Data Cleaning & Profiling

---

# Project Objectives
- Extract data from different sources.
- Clean and standardize raw datasets.
- Create calculated columns and conditional logic.
- Perform data profiling and quality checks.
- Merge and append multiple datasets.
- Transform datasets into analysis-ready format.
- Build reusable and dynamic Power Query workflows.

---

# Dataset Information
The project uses multiple datasets related to:
- Sales Data
- Employee Data
- Regional Information
- Monthly Performance Data

The datasets are transformed and combined inside Power Query for analytical purposes.

---

# Power Query Tasks Implemented

## 1. Data Extraction
- Loaded HTML table data from web sources.
- Imported Excel files from local folders.
- Connected CSV and Excel datasets.
- Loaded employee datasets containing:
  - Employee ID
  - Employee Name
  - Department
  - Region
  - Joining Date

---

## 2. Basic Data Transformation
- Removed blank rows and columns.
- Promoted first row as headers.
- Renamed columns for better readability.
- Changed data types appropriately.
- Removed duplicate and null values.
- Standardized numeric and currency formats.

---

## 3. Text Transformation
Used various text functions for data cleaning:
- UPPER()
- LOWER()
- TRIM()
- CLEAN()
- REPLACE()
- Split Column by Delimiter

Purpose:
- Standardize customer names.
- Clean address and text fields.
- Remove unwanted spaces and characters.

---

## 4. Numeric Transformations
- Rounded revenue values to 2 decimal places.
- Created calculated columns:
  - Revenue
  - Cost
  - Profit = Revenue – Cost

---

## 5. Date & Time Transformations
Extracted and created:
- Day
- Month
- Year
- Quarter

Additional transformations:
- Created Fiscal Month column.
- Calculated Age column from Birthdate.
- Performed custom date formatting.

---

## 6. Conditional Columns & Indexing
Created conditional columns based on sales values:
- High Sales
- Medium Sales
- Low Sales

Additional tasks:
- Added Index Column
- Created custom conditional logic

---

## 7. Pivoting & Unpivoting
- Pivoted sales data.
- Unpivoted monthly columns into normalized format.
- Converted wide-format data into analytical table structure.

---

## 8. Merging & Appending
Performed:
- Merge Queries
- Append Queries

Merged datasets using:
- Employee ID
- Region

Appended:
- January Sales
- February Sales
- March Sales
- Quarterly datasets

---

## 9. Grouping & Aggregation
Applied grouping operations to calculate:
- Total Sales
- Average Order Value
- Transaction Count
- Department-wise Performance
- Region-wise Analysis

---

## 10. Data Profiling & Quality Checks
Used Power Query profiling tools:
- Column Profile
- Column Distribution
- Column Quality

Performed checks for:
- Null values
- Errors
- Duplicate records
- Unique value distribution

---

## 11. Source Settings & Parameters
- Configured dynamic folder path parameters.
- Managed data source credentials.
- Used parameterized queries for flexible loading.

---

## 12. Refresh Simulation
- Simulated new monthly file uploads.
- Verified auto-refresh functionality.
- Ensured transformation steps remain consistent.

---

# Key Learnings
Through this project, the following concepts were practiced:
- Data Cleaning
- ETL Process
- Data Transformation
- Query Optimization
- Data Modeling Preparation
- Business Data Standardization
- Dynamic Data Loading
- Power Query Automation

---

# Business Use Cases
This project can be used for:
- Sales Reporting
- HR Analytics
- Regional Performance Tracking
- Financial Analysis
- Automated Data Preparation
- Dashboard Development

---

# Project Workflow
1. Import Raw Data
2. Clean & Transform Data
3. Apply Business Rules
4. Merge & Append Datasets
5. Validate Data Quality
6. Create Analytical Tables
7. Prepare Data for Dashboarding

---

# File Included
- `.pbix` Power BI Project File
- Power Query Transformations
- Data Cleaning Steps
- Aggregation & Profiling Operations

---

# Conclusion
This Power BI Power Query Transformation Project demonstrates real-world ETL and data preparation techniques used in business intelligence workflows. The project highlights the ability to clean, structure, transform, and combine multiple datasets into a reporting-ready format for dashboard creation and business analysis.

---
