# Pandas
# 📊 Data Analysis Projects

This repository contains **two main data analysis projects** implemented in Jupyter Notebooks, focusing on the **Indian Premier League (IPL)** and the **Fortune 500 US Companies** datasets. Each project involves **data cleaning, preprocessing, exploratory data analysis (EDA)**, and **visualizations** using Python libraries like Pandas, Matplotlib, and Seaborn.

---

## 📁 Project Structure
Pandas/
├── Companies.ipynb # Fortune 500 companies analysis
├── IPLAnalysis.ipynb # IPL matches & deliveries analysis
├── Fortune500CompaniesUS.csv # Dataset for Fortune 500 project
├── matches - matches.csv # IPL match details dataset
└── deliveries.csv # IPL ball-by-ball dataset

---

## ⚡ 1. IPL Analysis
**Notebook:** `IPLAnalysis.ipynb`  
**Datasets:**  
- `matches - matches.csv` → Match-level details (season, teams, winner, etc.)  
- `deliveries.csv` → Ball-by-ball deliveries data (runs, wickets, extras, etc.)

### Key Analysis Steps:
- Data loading & preprocessing  
- Handling missing values & data types  
- Match statistics (top teams, toss impact, winning patterns)  
- Batsmen and bowlers performance analysis  
- Heatmaps (e.g., number of 6s per team per over)  
- Correlation analysis between numeric features

### Libraries Used:
- `pandas`, `numpy` for data handling  
- `matplotlib`, `seaborn` for visualizations  

---

## ⚡ 2. Fortune 500 Companies Analysis
**Notebook:** `Companies.ipynb`  
**Dataset:**  
- `Fortune500CompaniesUS.csv` → Company name, industry, revenue, profits, employees, etc.

### Key Analysis Steps:
- Data preprocessing & cleaning  
- Top companies by revenue and profit  
- Industry-wise analysis  
- Correlation between revenue, profit, and number of employees  
- Visualizations of trends and distributions

### Libraries Used:
- `pandas`, `numpy` for analysis  
- `matplotlib`, `seaborn` for charts  

---
Install dependencies:

pip install pandas numpy matplotlib seaborn


Open Jupyter Notebook:

jupyter notebook


Open the .ipynb files and run all cells.
