# Data Analyst Internship - Task 1: Data Cleaning and Preprocessing

## Project Overview
This project focuses on cleaning and preprocessing a raw dataset containing missing values, duplicate entries, and inconsistent formatting using Python and Pandas. The cleaned dataset is prepared for further data analysis and visualization.

## Dataset Used
- **Name:** Netflix Movies and TV Shows
- **Source:** Kaggle

## Tools & Libraries Used
- **Language:** Python
- **Environment:** JupyterLab / Jupyter Notebook
- **Library:** Pandas

---

## Data Cleaning Summary & Steps Taken

1. **Standardized Column Headers:**
   - Converted all column names to lowercase, stripped extra whitespaces, and replaced spaces with underscores (`_`) for consistency.

2. **Handled Duplicate Records:**
   - Checked for duplicate rows using `.drop_duplicates()` and removed any redundant entries to maintain data integrity.

3. **Handled Missing Values:**
   - Replaced missing values in categorical text columns (`director`, `cast`, `country`) with `'Unknown'`.
   - Removed rows with critical missing values in `date_added`, `rating`, and `duration` using `.dropna()`.

4. **Data Type & Format Corrections:**
   - Trimmed leading/trailing whitespaces across string columns (`type`, `title`, `country`, `rating`).
   - Converted the `date_added` column to standard `datetime` format (`YYYY-MM-DD`) using `pd.to_datetime()`.

---

## Deliverables Included
- `netflix_movies.csv` (Raw Dataset)
- `cleaned_netflix_movies.csv` (Cleaned & Processed Dataset)
- Python Notebook / Code Script (`.ipynb` / `.py`)
- `README.md` (Project Documentation)


<img width="1897" height="902" alt="1" src="https://github.com/user-attachments/assets/4283f599-7866-4457-b1b1-7d1fe376cd2e" />

