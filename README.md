Markdown
# LAB 1 - How to Store an AI Dataset?
## Data Storage Methods in AI Systems

**Group Members:**  
* **Rinkle Sharma** (Student ID: 67784)  
* **Saisri Akkireddi** (Student ID: 66918)  
* **Submission:** Group of two students  

---

## Overview
This repository contains the solution and implementation for **Lab 1**, covering Tasks 1 through 6 on AI dataset storage architecture, format comparisons (**CSV vs. JSON vs. Parquet**), and analytical querying using **DuckDB** and **Pandas**. All numerical results, performance timings, and plots are generated dynamically by the notebook.

---

## Prerequisites & Reproduction
The synthetic dataset (100,000 rows) is generated locally when running the notebook; no external input files are required.

1. **Install dependencies:**
   ```bash
   pip install pandas numpy pyarrow duckdb matplotlib
Run the notebook:
lab1_notebook.ipynbOpen in Jupyter Lab or VS Code and run all cells in order. The notebook will create its local dataset inside alab1_data directory.

Summary of Tasks
Task 1: Designed a scalable storage architecture for a 10M+ image classification system.

Task 2: Generated a synthetic unbalanced metadata DataFrame across 5 categories.

Task 3 & 4: Benchmarked write times, read times, and file sizes across CSV, JSON, and Parquet formats.

Task 5 & 6: Executed filtering, sorting, aggregations, and multi-column joins using DuckDB.


---

### 4. Quick `.gitignore` Suggestion
Create a file named `.gitignore` in your root folder and add the following line so that temporary local data isn't unnecessarily pushed to GitHub:
```text
lab1_data/
.ipynb_checkpoints/
