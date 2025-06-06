# Titanic Dataset - Exploratory Data Analysis (EDA)

This repository contains the exploratory data analysis (EDA) of the Titanic dataset using Python, Pandas, Matplotlib, and Seaborn.

# Project Steps

1. **Data Reading**
   - Loaded the Titanic dataset using `pandas.read_csv()`

2. **Data Cleaning**
   - Handled missing values:
     - `Age`: Filled with median
     - `Embarked`: Filled with mode
     - `Cabin`: Dropped due to too many nulls
   - Removed duplicate entries
   - Detected and capped outliers in the `Fare` column using the 99th percentile

3. **Data Visualization**
   - Bar charts for categorical variables (e.g., `Sex`, `Pclass`, `Embarked`)
   - Histograms for numerical columns (`Age`, `Fare`)
   - Boxplots to identify outliers
   - Correlation heatmap for numerical features

4. **Summary of Observations**
   - Women had a significantly higher survival rate than men
   - Passengers in higher classes (`Pclass=1`) had better survival chances
   - Most passengers embarked from port `S`
   - Fare and Age have outliers that were handled for better analysis
   - `Fare` and `Pclass` show correlation with survival

---

# How to Run the Script

1. **Clone the Repository**

```bash
git clone https://github.com/SabeehUrRehmanKhan/Internship-tasks
cd Internship-tasks
cd "WEEK 1/TASK 1"

## 📁 Download only the `TASK 1` folder

You can browse or download only this folder:
👉 [View Folder on GitHub](https://github.com/SabeehUrRehmanKhan/Internship-tasks/tree/main/WEEK%201/TASK%201)

```

2. **Manage Resources**
- Setup a python virtual environment (optinal).
- Install required libraries.
- Run the task. 
