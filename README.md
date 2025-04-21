# Data-Cleaning-and-Processing
## 🎬 Movie Dataset — Cleaning & Preprocessing

This repository contains a data cleaning and preprocessing project for a movie metadata dataset.  
The original data was messy, inconsistent, and contained missing values — now it's clean, structured, and analysis-ready!

---

### 📁 Files in this repo

- <a href="https://github.com/LakshmiPriyanka13/Data-Cleaning-and-Processing/blob/main/movies.csv">movies.csv</a> — the initial uncleaned dataset 
- <a href="https://github.com/LakshmiPriyanka13/Data-Cleaning-and-Processing/blob/main/Data%20cleaning%20and%20Processing.ipynb">Data cleanin and Processing.ipynb</a> — Jupyter Notebook showing every cleaning step
- <a href="https://github.com/LakshmiPriyanka13/Data-Cleaning-and-Processing/blob/main/cleaned_data.csv">cleaned_data.csv</a> - the cleaned dataset
- <a href="https://github.com/LakshmiPriyanka13/Data-Cleaning-and-Processing/edit/main/README.md">README.md</a> —  This documentation file

---

### 🧹 Cleaning Workflow

Key steps performed in the notebook:
- Loaded dataset and inspected null values
- Removed special characters from GENRE, ONE-LINE, and STARS columns
- Converted year values to 4-digit standardized format
- Extracted Director and Stars from mixed string fields
- Removed special characters and normalized whitespace
- Handled null values (`NaN`) via filling or dropping
- Sorted movies by release year
- Exported final DataFrame to `cleaned_data.csv`

---

## 🔧 Tech Stack

- Python 
- Pandas 
- Jupyter Notebook 
