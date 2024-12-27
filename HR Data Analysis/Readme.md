# HR Data Analysis Project

## Overview

This project focuses on analyzing HR data to identify key patterns and insights. The dataset consists of various employee-related attributes such as age, education, job role, satisfaction levels, and more. The primary goals of this analysis were:

- Data cleansing and preparation.
- Extracting meaningful insights.
- Preparing the data for further analysis or modeling.

---

## Objectives

The main objectives of this project were:

1. **Data Cleaning**:
   - Remove unnecessary columns.
   - Rename columns for clarity.
   - Eliminate redundant entries and duplicates.
   - Handle missing and invalid values.
   - Sanitize specific columns for consistency.

2. **Exploratory Data Analysis (EDA)**:
   - Understand the structure and content of the data.
   - Prepare the data for visualization and modeling.

---

## Dataset Description

- **Total Records**: 1,470 rows
- **Total Columns**: 35 (reduced after cleaning)
- **Key Columns**:
  - `Age`: Employee's age.
  - `Attrition`: Whether the employee has left the company (Yes/No).
  - `BusinessTravel`: Frequency of business-related travel.
  - `DistanceFromHome`: Distance of the employee's home from work.
  - `JobSatisfaction`: Satisfaction level of the employee with their job.
  - `YearsAtCompany`: Number of years the employee has worked at the company.

---

## Cleaning Steps

The dataset was cleaned using the following steps:

1. **Removed Unnecessary Columns**:
   - Dropped constant-value columns such as `EmployeeCount` and `StandardHours`.

2. **Eliminated Duplicates**:
   - Removed redundant rows to ensure data integrity.

3. **Renamed Columns**:
   - Renamed columns to make them more intuitive (e.g., `DailyRate` → `daily_rate`).

4. **Sanitized Specific Columns**:
   - Standardized categorical values in the `BusinessTravel` column.
   - Converted binary categorical columns (e.g., `Attrition`) to numerical formats for analysis.

5. **Handled Missing Values**:
   - Checked for `NaN` values and removed affected rows.

6. **Validated Data Types**:
   - Ensured all columns had appropriate data types (e.g., numeric, categorical).

---

## Results and Insights

- **Data Cleansing**:
  - Reduced unnecessary columns and cleaned the dataset for efficient analysis.
  - Ensured no missing or duplicate values.

- **EDA Preparation**:
  - The cleaned dataset is now ready for exploratory data analysis and visualization.

---

## How to Use This Project

1. **Dependencies**:
   - Python 3.x
   - Required Libraries: `pandas`, `numpy`
2. **Run the Analysis**:
   - Use the Python scripts provided in the repository to reproduce the cleaning steps.
   - Adjust the cleaning or feature engineering as per specific use cases.
---
