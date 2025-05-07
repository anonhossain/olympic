# 🏅 Olympic Dataset Analysis Project

![Result](https://github.com/anonhossain/olympic/blob/main/result/Dashboard.PNG)

## 📌 Overview

This project focuses on analyzing Olympic Games data using **Python**, storing it efficiently with **PostgreSQL**, and visualizing insights through an interactive **Power BI** dashboard. It demonstrates advanced data cleaning techniques and integrates data science tools for end-to-end analysis.

---

## 🧪 Tools & Technologies Used

- **Python** (Pandas, NumPy)
- **PostgreSQL** (Data storage and querying)
- **Power BI** (Dashboard creation and insights visualization)
- **Jupyter Notebook** (Data preprocessing and scripting)
- **SQLAlchemy** (Python-PostgreSQL connection)

---

## 🔍 Key Features

- Advanced data cleaning using **Iterative Imputation** to handle missing values.
- Data stored in PostgreSQL for efficient querying.
- Power BI dashboard connected directly to the PostgreSQL database.
- Insightful graphs and metrics calculated with DAX in Power BI.

---

## 📊 Measures Used in Power BI

```DAX
total_games = DISTINCTCOUNT('public dataset'[Games])
total_regions = DISTINCTCOUNT('public dataset'[region]) 
total_countries = DISTINCTCOUNT('public dataset'[NOC])
```
