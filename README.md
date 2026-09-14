# customer_behavior_analysis
This is a data analytics project which showcases customer behavior using Python, SQL and Power BI
# 📊 Data Analytics Project

## Overview

This project demonstrates an end-to-end **data analytics workflow**, from loading and exploring raw data to generating business insights and presenting the results through an interactive Power BI dashboard and presentation.

The project combines **Python, PostgreSQL, Power BI, and Gamma** to transform raw data into meaningful insights that can support data-driven decision-making.

---

## 🎯 Project Objectives

* Load and understand the dataset using Python
* Perform Exploratory Data Analysis (EDA)
* Clean and prepare the data for analysis
* Store and query data using PostgreSQL
* Identify trends, patterns, and key business insights
* Build an interactive Power BI dashboard
* Create a written analytical report
* Present the findings using a professional PowerPoint presentation

---

## 📁 Dataset

The dataset contains business-related data used to explore trends, patterns, and performance indicators.

Key activities performed on the dataset included:

* Checking the dataset structure
* Identifying missing values
* Detecting duplicates
* Checking data types
* Identifying potential outliers
* Cleaning inconsistent data
* Preparing the data for SQL analysis and visualization

> **Dataset:** `dataset.csv`

---

## 🛠️ Tools & Technologies

| Tool                     | Purpose                           |
| ------------------------ | --------------------------------- |
| **Python**               | Data loading, cleaning and EDA    |
| **Pandas**               | Data manipulation and analysis    |
| **Matplotlib / Seaborn** | Data visualization during EDA     |
| **PostgreSQL**           | Data storage and SQL analysis     |
| **SQL**                  | Querying and extracting insights  |
| **Power BI**             | Interactive dashboard development |
| **Gamma**                | Presentation creation             |
| **Microsoft PowerPoint** | Final presentation                |

---

## 🔄 Project Workflow

### 1. Data Loading

The dataset was loaded into Python using Pandas.

```python
import pandas as pd

df = pd.read_csv("dataset.csv")

print(df.head())
print(df.info())
```

The initial analysis focused on understanding the dataset structure, columns, data types, and overall data quality.

---

### 2. Exploratory Data Analysis (EDA)

EDA was performed to understand the characteristics of the data and identify patterns or potential issues.

Key activities included:

* Reviewing descriptive statistics
* Analysing distributions
* Checking missing values
* Identifying duplicates
* Exploring relationships between variables
* Creating visualizations
* Identifying trends and anomalies

---

### 3. Data Cleaning

The dataset was cleaned before performing the final analysis.

Data preparation included:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Standardising values
* Checking for inconsistent records
* Validating the cleaned dataset

The goal was to ensure the data was accurate, consistent, and suitable for analysis.

---

### 4. PostgreSQL & SQL Analysis

The cleaned dataset was loaded into **PostgreSQL** for structured querying and analysis.

SQL was used to answer business questions and extract useful insights.

Examples of analysis included:

```sql
SELECT category, COUNT(*) AS total_records
FROM sales
GROUP BY category
ORDER BY total_records DESC;
```

Other SQL techniques used included:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `ORDER BY`
* Aggregate functions
* `CASE WHEN`
* `JOIN`
* Subqueries
* Common Table Expressions (CTEs)

---

### 5. Power BI Dashboard

The analysed data was connected to Power BI to create an interactive dashboard.

The dashboard provides an overview of key performance indicators and allows users to explore the data through filters and visualisations.

### Dashboard Features

* Key Performance Indicators (KPIs)
* Trend analysis
* Category analysis
* Regional/segment analysis
* Interactive filters
* Charts and visualisations
* Business insights

📌 **Dashboard:** `PowerBI/Dashboard.pbix`

*A screenshot of the dashboard can also be added to this section.*

---

## 📈 Key Results & Insights

The analysis identified several important trends and patterns within the dataset.

Key findings included:

* Identification of the highest-performing categories
* Analysis of trends over time
* Identification of important customer or business segments
* Detection of areas of strong and weak performance
* Data-driven observations that can support business decision-making

The detailed findings are available in the project report.

📄 **Report:** `Report/Analytics_Report.pdf`

---

## 📑 Project Presentation

The final insights were summarised in a professional presentation created using **Gamma** and exported to PowerPoint.

The presentation covers:

1. Project Overview
2. Business Objective
3. Dataset
4. Data Preparation
5. EDA Findings
6. SQL Analysis
7. Power BI Dashboard
8. Key Insights
9. Recommendations
10. Conclusion

📊 **Presentation:** `Presentation/Data_Analytics_Presentation.pptx`

---

## 📂 Project Structure

```text
Data-Analytics-Project/
│
├── data/
│   └── dataset.csv
│
├── python/
│   └── analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── report/
│   └── analytics_report.pdf
│
├── presentation/
│   └── data_analytics_presentation.pptx
│
└── README.md
```

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/data-analytics-project.git
```

### 2. Install Python Dependencies

```bash
pip install pandas matplotlib seaborn jupyter
```

### 3. Run the Python Analysis

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
python/analysis.ipynb
```

### 4. Set Up PostgreSQL

Create a PostgreSQL database and import the cleaned dataset.

Update the database connection details in the Python notebook or SQL workflow as required.

Run the SQL queries located in:

```text
sql/analysis_queries.sql
```

### 5. Open the Power BI Dashboard

Open:

```text
powerbi/dashboard.pbix
```

If necessary, update the data source connection to your local PostgreSQL database.

---

## 💡 Business Value

This project demonstrates the ability to take a dataset from **raw data to actionable business insights**.

It showcases practical skills in:

* Data cleaning
* Exploratory data analysis
* SQL
* PostgreSQL
* Data visualisation
* Power BI
* Business analysis
* Data storytelling
* Presenting insights to stakeholders

---

## 👤 Author

**Bontle Malope**

Data Analyst | Data Science Student

[LinkedIn](https://www.linkedin.com/in/bontle-malope-329a32244/)

---

## ⭐ Conclusion

This project demonstrates an end-to-end approach to data analytics, combining technical analysis with business-focused storytelling.

The workflow moves from:

**Raw Data → Python → EDA → Data Cleaning → PostgreSQL/SQL → Power BI → Insights → Report → Presentation**

The objective is not only to analyse data, but to communicate the findings clearly and turn analysis into insights that can support better business decisions.
