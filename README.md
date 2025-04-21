# Data-Cleaning-and-Processing
## 🎬 Movie Dataset — Cleaning & Preprocessing

This repository contains a data cleaning and preprocessing project for a movie metadata dataset.  
The original data was messy, inconsistent, and contained missing values — now it's clean, structured, and analysis-ready!

---

### 📁 Files in this repo

- `movies.csv` — ✅ Final cleaned dataset in CSV format
- `Data cleaning and Processing.ipynb` — 📓 Jupyter Notebook showing every cleaning step
- `README.md` — 📘 This documentation file

---

### 🧹 Cleaning Workflow

Key steps performed in the notebook:

- Converted year values to 4-digit standardized format
- Extracted Director and Stars from mixed string fields
- Removed special characters and normalized whitespace
- Handled null values (`NaN`) via filling or dropping
- Sorted movies by release year
- Exported final DataFrame to `movies.csv`

---

## 🔧 Tech Stack

- Python 🐍
- Pandas 📊
- Jupyter Notebook 📒
