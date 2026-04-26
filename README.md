# 🛒 E-Commerce Sales Analysis — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-EDA-green?logo=pandas)
![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-20BEFF?logo=kaggle)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Overview

This project performs an end-to-end **Exploratory Data Analysis (EDA)** on a real-world e-commerce retail transaction dataset sourced from Kaggle. The dataset contains over **530,000 transactions** from a UK-based online store, covering customers across multiple countries.

The goal is to clean the raw data, understand its structure, and extract meaningful insights through visualization.

---

## 📋 Table of Contents

- [Dataset](#-dataset)
- [Project Workflow](#-project-workflow)
- [Key Findings](#-key-findings)
- [Visualizations](#-visualizations)
- [Tools Used](#-tools-used)
- [How to Run](#-how-to-run)
- [Author](#-author)

---

## 📂 Dataset

| Property | Details |
|----------|---------|
| Source | [Kaggle — Online Retail Dataset](http://localhost:8888/files/ecommercesales.ipynb?_xsrf=2%7C39968064%7Cc5e5bfe1f5a00cd07890da371904ebfe%7C1776236868) |
| Rows | 531,150 |
| Columns | 8 |
| Date Range | December 2018 – December 2019 |

**Columns:**
- `TransactionNo` — Unique transaction ID
- `Date` — Date of purchase
- `ProductNo` — Product identifier
- `ProductName` — Name of the product
- `Price` — Unit price (GBP)
- `Quantity` — Units purchased (negative = cancellation)
- `CustomerNo` — Unique customer ID
- `Country` — Customer's country

---

## 🔄 Project Workflow

### 1. 🔍 Data Understanding
- Inspected shape, data types, and sample records
- Identified column meanings and relationships
- Detected missing values and data quality issues

### 2. 🧹 Data Cleaning
- Handled missing `CustomerNo` values
- Removed duplicate transaction records
- Filtered out cancelled orders (transactions with negative quantity)
- Standardized date formats for time-based analysis

### 3. 📊 Visualization
- Analyzed revenue distribution across countries
- Identified top contributing markets
- Explored purchasing patterns by region

---

## 💡 Key Findings

- 🇬🇧 **United Kingdom** dominates revenue, accounting for the majority of all transactions
- 🌍 **Germany, France, and EIRE** are the next highest revenue-generating countries
- ❌ A small percentage of transactions are **cancellations** (negative quantity values)
- 🧾 A large share of customers have **no recorded CustomerNo**, indicating guest checkouts

---

## 📊 Visualizations

### Revenue by Country
> *(Add your chart image here — drag and drop into the GitHub repo and paste the link)*

```markdown
![Revenue by Country](images/revenue_by_country.png)
```

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data cleaning & manipulation |
| Matplotlib | Data visualization |
| Seaborn | Statistical plotting |
| Jupyter Notebook | Interactive analysis environment |

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/barath/ecommerce-sales-eda

# 2. Navigate into the project folder
cd ecommerce-sales-eda

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch Jupyter Notebook
jupyter notebook notebooks/eda_analysis.ipynb
```

---

## 👤 Author

**Barath**
- 🔗 [LinkedIn]([https://www.linkedin.com/in/](https://www.linkedin.com/in/barathan--s/))
- 🐙 [GitHub]((https://github.com/Barathan2006))

---

> ⭐ If you found this project useful, feel free to star the repo!
