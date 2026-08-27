# 🏥 Medical Appointment No Shows — Data Cleaning

A small data cleaning project completed as part of my **Elevate Labs Data Analyst Internship**.

## 📂 Dataset

Used the **Medical Appointment No Shows** dataset from Kaggle.

* 📊 Original dataset: [`Medical_Appointment_No_Shows.csv`](Medical_Appointment_No_Shows.csv)
* 🧹 Cleaned dataset: [`Medical_Appointment_No_Shows_Cleaned.csv`](Medical_Appointment_No_Shows_Cleaned.csv)
* 🐍 Python code: [`python_code.ipynb`](data_cleaning.ipynb)

## 🔧 What I Did

* Checked for missing values and duplicates
* Removed 1 invalid age value (`-1`)
* Removed 5 invalid date records
* Converted date columns to datetime format
* Standardized column names to lowercase `snake_case`
* Corrected inconsistent column names
* Checked categorical and numerical values
* Performed final data validation

<details>
<summary>📌 Final Dataset</summary>

After cleaning, the dataset contains **110,521 rows and 14 columns** with no missing values or duplicate rows.

</details>

## 🛠️ Tools Used

**Python • Pandas • Jupyter Notebook**
