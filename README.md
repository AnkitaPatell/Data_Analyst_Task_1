#  Task 1: Data Cleaning and Preprocessing

##  Objective

This project is part of a Data Analyst Internship and focuses on cleaning and preparing a raw dataset by addressing common data quality issues such as missing values, duplicates, inconsistent formats, and incorrect data types.

---

## Dataset

**Customer Personality Analysis**  
Source: [Kaggle](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)  
This dataset contains detailed analysis of a company’s ideal customers.

---

## Tools Used

- **Python** (pandas)
- **Microsoft Excel**

---

## Tasks Performed

1. **Handled Missing Values**  
   - Identified using `.isnull()` in pandas  
   - Filled or removed based on context (e.g., dropping rows with missing `Income`)

2. **Removed Duplicates** 
   - Used `.duplicated()` in pandas to identify the duplicated rows 
   - Used `.drop_duplicates()` in pandas and "Remove Duplicates" in Excel

3. **Standardized Text Formats**  
   - Used unique() function of pandas to check for the inconsistently in the column values.
   - Cleaned values in categorical fields wherever required.
   - Ensured consistent case and spacing 
   
4. **Converted Dates**  
   - Standardized date columns (e.g., `Dt_Customer`) to `dd-mm-yyyy` format using `pd.to_datetime()`

5. **Renamed Column Headers**  
   - Renamed column name from 'Dt_Customer' to 'Cust_Enroll_Date' for better understanding
   - Replaced column name from 'Status_Marital' to 'Marital_Status'

6. **Fixed Data Types** 
   - Used info() and dtype functions of  pandas to check datatypes
   - Ensured numerical columns are `int` or `float`  
   - Converted date columns to `datetime64[ns]`

---

##  Cleaned Dataset

The cleaned and processed version of the dataset is included as:- `Processed_marketing_campaign_data.xlsx`

---
