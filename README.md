# SWYNEX Data Cleaning & Preparation

## Internship Task 1 – Data Cleaning & Preparation

This project was completed as part of the **SWYNEX Data Analyst Internship**.

### 📌 Project Overview

The objective of this task was to clean and prepare a public retail sales dataset for further data analysis.

The dataset contains information about orders, customers, categories, locations, sales, discounts, and profits.

### 🛠️ Tools Used

* Python
* Pandas
* Google Colab
* GitHub

### 📊 Dataset

**Dataset:** Supermart Grocery Sales / Retail Sales Dataset
**Format:** CSV

The dataset contains the following major columns:

* Order ID
* Customer Name
* Category
* Sub Category
* City
* Order Date
* Region
* Sales
* Discount
* Profit
* State

### 🧹 Data Cleaning Performed

The following data-quality checks and cleaning steps were performed:

1. **Missing Values**

   * Checked all columns for missing values.
   * No missing values were found.

2. **Duplicate Records**

   * Checked the dataset for duplicate rows.
   * No duplicate records were found.

3. **Date Format**

   * The `Order Date` column originally contained dates in mixed formats.
   * The column was converted from an object/string type to a proper `datetime` format using Pandas.

4. **Data Types**

   * Checked the data types of the dataset columns.
   * Numeric and categorical columns were reviewed for consistency.

5. **Categorical Values**

   * Reviewed categories, sub-categories, and regions for inconsistent values.

### ✅ Final Result

After the cleaning and preparation process, the dataset was checked for:

* Missing values
* Duplicate records
* Incorrect date formats
* Data type issues
* Inconsistent categorical values

The cleaned dataset is available in this repository as:

`SWYNEX_Data_Cleaned.csv`

### 📁 Repository Contents

| File                      | Description                  |
| ------------------------- | ---------------------------- |
| `SWYNEX_Data_Cleaned.csv` | Cleaned and prepared dataset |
| `README.md`               | Project documentation        |

### 🎯 Learning Outcomes

Through this task, I gained practical experience in:

* Data cleaning using Python and Pandas
* Handling and checking missing values
* Detecting duplicate records
* Converting date formats
* Checking data types
* Preparing datasets for further analysis
* Using GitHub to document and submit a data analytics project

### 👩‍💻 Internship

**Organization:** SWYNEX Technologies
**Role:** Data Analyst Intern
**Task:** Data Cleaning & Preparation

---

**Author:** Akanksha Rajak
**GitHub:** `@akanksha778`
