# 🐍 Data Technician Workbook - Python | Just IT's Data Skills Bootcamp [(PDF)](https://github.com/nathan-mullings-dev/python-project-justit/blob/main/Data%20Technician%20Workbook%20-%20Python.pdf)

---

## 📘 Project Overview

This repository contains my completed Python workbook from the **JustIT Data Technician Skills Bootcamp**. The workbook includes foundational Python programming tasks and hands-on data manipulation using Pandas — preparing me for real-world data analysis workflows.

Over several sessions, I practiced key Python concepts, wrote scripts, loaded and explored datasets, and performed basic data transformations in preparation for entry-level data roles.

---

## 🧪 Exercises Included

### ✅ Python Fundamentals

#### 🔹 FizzBuzz Challenge
- Classic logic problem used in interviews
- Python script iterating from 1–100:
  - Print "fizz" for multiples of 3
  - Print "buzz" for multiples of 5
  - Print "fizzbuzz" for multiples of both
  - Print number otherwise

---

### ✅ Data Exploration with Pandas

#### 📂 Exercise 1: Loading and Exploring CSV Data
- `read_excel()` and `read_csv()` with Pandas
- Used `.head()`, `.info()`, `.describe()` to explore structure and summary statistics

#### 🧮 Exercise 2: Indexing and Slicing
- Select single and multiple columns
- Filter rows using `.iloc[]`, `.loc[]`, and conditional logic
- Example: Filter students in class "Four" using `df.loc[df["class"]=="Four"]`

#### 🔧 Exercise 3: Data Manipulation
- Add a new column (`passed`) based on conditional logic
- Rename columns (`mark` ➝ `score`)
- Drop columns (`passed`)
- Update the DataFrame in-place

---

### ✅ Working with External Datasets

#### Dataset: *GDP (Nominal) per Capita*
- Loaded Excel data into Pandas using `read_excel()`
- Displayed:
  - First 10 rows (`df.head(10)`)
  - Last 5 rows (`df.tail(5)`)
  - Specific columns like `['Country/Territory', 'UN_Region']`

---

## 🛠️ Tools & Libraries

- **Python 3**
- **Pandas** for data analysis
- **Jupyter Notebook / Google Colab**
- **Excel & CSV file handling**

---

## 🎓 Learning Outcomes

By completing this workbook, I developed key Python programming and data analysis skills:

- 🧠 Improved my understanding of control flow (if-else, loops)
- 📄 Learned how to read and explore real-world datasets using Pandas
- 📊 Practiced slicing, indexing, filtering, and manipulating tabular data
- 🛠️ Understood how to apply logic to create new columns or update structures
- 💡 Built confidence using Python in Jupyter and Google Colab environments
- ✅ Practiced using Python for **data preprocessing**, a key step in analytics workflows
