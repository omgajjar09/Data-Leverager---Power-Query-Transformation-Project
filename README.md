# 🚀 Data Leverager – Power Query Transformation Project

---

# 📌 Project Overview

This project demonstrates a complete **ETL (Extract, Transform, Load)** workflow using **Microsoft Power BI** and **Power Query Editor**.

The project focuses on:
- Cleaning raw business data
- Transforming datasets into analytical format
- Creating reusable Power Query workflows
- Performing data profiling & quality checks
- Merging and appending multiple datasets
- Preparing data for dashboard reporting

This project simulates real-world business scenarios such as:
- 📈 Sales Analysis
- 👨‍💼 Employee Management
- 🌍 Regional Reporting
- 💰 Financial Calculations

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|------|----------|
| 📊 Power BI | Data Visualization & Modeling |
| 🔄 Power Query | Data Transformation |
| 📑 Excel / CSV | Data Sources |
| 🧮 DAX | Calculated Columns & Measures |
| 📂 Folder Connection | Dynamic Data Loading |

---

# 🎯 Project Objectives

✅ Import data from multiple sources  
✅ Clean and standardize datasets  
✅ Create calculated and conditional columns  
✅ Perform data profiling & quality validation  
✅ Merge and append datasets dynamically  
✅ Prepare data for dashboard analysis  
✅ Build scalable Power Query transformations  

---

# 📂 Dataset Information

The project includes multiple datasets related to:

- 📈 Sales Data
- 👨‍💼 Employee Data
- 🌍 Region Information
- 📅 Monthly Performance Data

All datasets were transformed and structured using Power Query Editor.

---

# ⚙️ Power Query Tasks Implemented

---

## 1️⃣ Data Extraction

### Tasks Performed:
- 🌐 Loaded HTML table data from web sources
- 📂 Imported Excel files from folders
- 📄 Connected CSV & Excel datasets
- 👨‍💼 Loaded Employee datasets

### Employee Dataset Includes:
- Employee ID
- Employee Name
- Department
- Region
- Joining Date

---

## 2️⃣ Basic Data Transformation

### Implemented:
- ❌ Removed blank rows & columns
- 🔝 Promoted first row as headers
- ✏️ Renamed columns
- 🔄 Changed data types
- 🧹 Removed duplicates & null values
- 💲 Standardized currency formats

---

## 3️⃣ Text Transformation

### Text Functions Used:
```powerquery
UPPER()
LOWER()
TRIM()
CLEAN()
REPLACE()
Split Column by Delimiter
```

### Purpose:
- Standardize customer names
- Clean address fields
- Remove unwanted spaces & characters

---

## 4️⃣ Numeric Transformations

### Created:
- 💰 Revenue Column
- 💸 Cost Column
- 📊 Profit Column

### Formula:
```text
Profit = Revenue - Cost
```

### Additional Tasks:
- Rounded revenue values to 2 decimal places

---

## 5️⃣ Date & Time Transformations

### Extracted:
- 📅 Day
- 📆 Month
- 🗓️ Year
- 📈 Quarter

### Additional Features:
- Fiscal Month Column
- Age Calculation from Birthdate
- Custom Date Formatting

---

## 6️⃣ Conditional Columns & Indexing

### Conditional Logic:
| Sales Value | Category |
|-------------|----------|
| > 1000 | High Sales |
| 500 - 999 | Medium Sales |
| < 500 | Low Sales |

### Additional Tasks:
- 🔢 Added Index Column
- ⚡ Created custom conditional columns

---

## 7️⃣ Pivoting & Unpivoting

### Implemented:
- Pivot Columns
- Unpivot Monthly Data
- Converted wide tables into normalized format

---

## 8️⃣ Merging & Appending

### Merge Queries:
Merged datasets using:
- Employee ID
- Region

### Append Queries:
- January Sales
- February Sales
- March Sales
- Quarterly Data

---

## 9️⃣ Grouping & Aggregation

### Aggregations Performed:
- 📊 Total Sales
- 💵 Average Order Value
- 🔢 Transaction Count
- 🏢 Department-wise Analysis
- 🌍 Region-wise Analysis

---

## 🔟 Data Profiling & Quality Checks

### Power Query Tools Used:
- Column Profile
- Column Distribution
- Column Quality

### Validation Checks:
- Null Values
- Errors
- Duplicate Records
- Unique Values

---

## 1️⃣1️⃣ Source Settings & Parameters

### Configurations:
- Dynamic Folder Path Parameters
- Data Source Credentials
- Parameterized Queries

---

## 1️⃣2️⃣ Refresh Simulation

### Implemented:
- Simulated monthly file uploads
- Tested auto-refresh functionality
- Verified transformation consistency

---

# 📚 Key Learnings

This project helped practice:

- ✅ ETL Workflow
- ✅ Data Cleaning
- ✅ Query Optimization
- ✅ Power Query Automation
- ✅ Business Data Standardization
- ✅ Data Modeling Preparation
- ✅ Dynamic Data Loading

---

# 💼 Business Use Cases

This project can be applied to:

| Use Case | Description |
|----------|-------------|
| 📈 Sales Reporting | Track business performance |
| 👨‍💼 HR Analytics | Analyze employee data |
| 🌍 Regional Analysis | Compare regional performance |
| 💰 Financial Reporting | Revenue & profit analysis |
| 📊 Dashboard Preparation | Reporting-ready datasets |

---

# 🔄 Project Workflow

```text
Import Raw Data
        ↓
Clean & Transform Data
        ↓
Apply Business Rules
        ↓
Merge & Append Datasets
        ↓
Validate Data Quality
        ↓
Create Analytical Tables
        ↓
Prepare Dashboard Dataset
```

---

# 📁 Files Included

```text
📦 Project Files
 ┣ 📊 Power BI (.pbix)
 ┣ 🔄 Power Query Transformations
 ┣ 📑 Data Cleaning Steps
 ┗ 📈 Aggregation & Profiling Operations
```

---

# 🏆 Project Highlights

✨ Real-world ETL workflow  
✨ Multiple data source integration  
✨ Advanced Power Query transformations  
✨ Dynamic parameter handling  
✨ Business-ready analytical dataset  

---

# 📌 Conclusion

This project demonstrates how Power BI and Power Query can be used to build a complete data transformation pipeline for business intelligence solutions.

The workflow includes:
- Data extraction
- Cleaning
- Transformation
- Aggregation
- Profiling
- Automation

The final output is a structured, analysis-ready dataset suitable for dashboard development and reporting.

---
