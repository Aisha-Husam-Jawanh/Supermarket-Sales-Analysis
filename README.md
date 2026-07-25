# 📊 Supermarket Sales Analysis — Data Pipeline & OOP Framework

An end-to-end Python data analysis project built for the **Data Science Programming Languages (Lab) - DSAI 1103** course. This repository demonstrates core data engineering concepts, Object-Oriented Programming (OOP) with custom exception handling, high-performance vectorized operations with NumPy, and automated data processing with Pandas exported into a multi-sheet Excel report.

---

## 🚀 Project Milestones

### 🛒 Milestone 1: Kaggle Data Loading
- Configured Kaggle API access token programmatically in Google Colab.
- Automated downloading and extraction of the Supermarket Sales Dataset.
- Inspected structure, shape, and column data types using Pandas.

### ⚙️ Milestone 2: Python Core & OOP Architecture
- Applied foundational Python functions (`map`, `filter`, `lambda`, list comprehensions, sorting) on transaction records.
- Built a custom `InvalidTransactionError` exception to handle strict data validation (price, quantity, rating).
- Designed an Object-Oriented system:
  - **Base Class:** `SaleTransaction` (Encapsulating price, quantity, and rating validation).
  - **Derived Classes:** `NormalSale` and `MemberSale` (Implementing **Polymorphism** for dynamic discount calculations).

### 🔢 Milestone 3: Vectorized Analysis with NumPy
- Converted dataset features into high-performance NumPy arrays (`prices`, `quantities`).
- Performed zero-loop vectorized matrix multiplications for line totals.
- Executed Boolean indexing to isolate high-value transactions (> $300).
- Computed core descriptive statistics (**Mean**, **Max**, **Min**, **Standard Deviation**).

### 🐼 Milestone 4: Pandas Cleaning, Aggregation & Excel Automation
- Handled missing data, duplicate rows, space stripping, and date-time type conversion.
- Aggregated sales metrics across branches and product categories.
- Generated dynamic Pivot Tables breaking down revenue by branch and payment methods.
- Automated multi-sheet output exporting data to `Supermarket_Sales_Report.xlsx` using `openpyxl`.

---

## 🛠️ Tech Stack

- **Language:** Python 3
- **Data Libraries:** Pandas, NumPy, OpenPyXL
- **Environment:** Google Colab / Jupyter Notebook
- **Version Control:** Git & GitHub

---

## 👩‍💻 Author

- **Aisha Husam Jawanah** (Student ID: 220259212) — *Data Science & AI Engineering Student*
- **Institution:** University College of Applied Sciences (UCAS)
