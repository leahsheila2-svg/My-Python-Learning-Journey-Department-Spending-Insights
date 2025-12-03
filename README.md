# Beginner Python Project: Department Spending Analysis

This project demonstrates beginner‑friendly Python data analysis using **pandas** and **matplotlib**.  
It takes raw transaction data and walks through the full workflow: cleaning messy fields, validating column names, converting amounts to numeric, and aggregating total spending by department.  
The analysis produces polished visualizations with professional formatting, saved as images for quick review.

##  Objectives
- Clean and validate transaction data
- Aggregate spending by department
- Visualize results with professional formatting
- Document workflow for clear evaluation

##  Workflow
1. **Load data** → import CSV into pandas DataFrame
2. **Inspect & clean** → validate column names, convert amounts to numeric
3. **Aggregate** → group by department and sum spending
4. **Validate** → check for missing values, duplicates, and data types
5. **Visualize** → plot line chart with Cambria font, comma formatting, rotated labels
6. **Export outputs** → save cleaned CSV and chart image into respective folders

## 📊 Outputs
- **CSV summary:** `data/department_spending_summary.csv`
- **Line chart:** `images/department_spending_line.png`

##  Outputs
 
- **Line chart:** `Image/department_spending.jpg`

Preview:  
![Department spending line chart](Image/department_spending.jpg)


##  Future Improvements
- Add bar chart with labels for exact totals
- Automate cleaning in a script (`clean_and_group.py`)
- Add unit tests for schema validation
- Build a simple Streamlit dashboard for interactivity
