# 🚗 Car Dataset Analysis Project

This project is focused on basic data cleaning and analysis of a car dataset using **Pandas** in Python. It is a beginner-friendly project designed to demonstrate fundamental data wrangling, filtering, and transformation operations.

## 📁 Files in Repository

- `Car_subProject_analysis.ipynb`: Jupyter notebook with step-by-step analysis.
- `Car_Question_for_analysis.txt`: Instructions/questions for analysis tasks.

## 🔧 Technologies Used

- Python 🐍
- Jupyter Notebook 📓
- Pandas 🐼

## 📊 Objective

Perform data cleaning and basic analysis operations on a car dataset including:

- Handling missing data
- Understanding unique values and their frequencies
- Filtering based on conditions
- Removing unwanted records
- Applying functions to transform data

---

## 📌 Analysis Tasks Performed

1. **Handling Null Values**  
   - Detected missing values using `df.isnull().sum()`  
   - Filled missing values with the **mean** of their respective columns using `fillna()`

2. **Value Counts**  
   - Identified all unique values in the `Make` column using `value_counts()`

3. **Filtering Records**  
   - Displayed records where `Origin` is either **Asia** or **Europe** using `isin()`

4. **Removing Records**  
   - Removed all rows where `Weight > 4000` using a conditional filter

5. **Column Transformation**  
   - Increased all values in `MPG_City` column by 3 using `apply()` function

---

## 🔍 Commands and Functions Used

| Function/Command       | Purpose                                                |
|------------------------|--------------------------------------------------------|
| `import pandas as pd`  | Import Pandas library                                  |
| `pd.read_csv()`        | Load CSV file                                          |
| `df.head()`            | View first few rows of the dataset                     |
| `df.shape`             | Get number of rows and columns                         |
| `df.isnull().sum()`    | Count missing values per column                        |
| `df.fillna(value)`     | Fill missing values                                    |
| `df['col'].value_counts()` | Get frequency of unique values                     |
| `df[df['col'].isin([...])]` | Filter rows based on column values                |
| `df['col'].apply(lambda x: x+3)` | Apply a function to a column                 |

---

## ✅ Outcomes

- Cleaned and structured dataset ready for deeper analysis.
- Gained insights into data distribution and characteristics.
- Practiced essential data manipulation techniques in Pandas.

---

## 📌 Note

This project is ideal for beginners looking to practice:
- Data cleaning
- EDA (Exploratory Data Analysis)
- Pandas functions and filters

---

## 📬 Contact

Feel free to connect with me if you have questions or suggestions!

> 💡 Tip: Don't forget to ⭐ the repo if you found it useful!

