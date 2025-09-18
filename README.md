# Bank Customer Churn Analysis

**Analyst:** Krastiu Dimov  
**Tools Used:** SQL, Python, Power BI  

---

## Project Overview
This project analyzes customer churn in a retail banking dataset to identify key factors driving attrition and provide actionable retention strategies. Insights are delivered using SQL for data extraction and cleaning, Python for analysis, and Power BI for visualization.

---

## Business Challenge
Customer churn leads to revenue loss and higher acquisition costs. The goal is to identify high-risk segments and offer data-backed strategies to reduce churn, optimize product offerings, and improve customer retention.

---

## Key Findings
- Female and middle-aged clients (35–54) are more likely to churn.
- German clients have the highest churn rate (32.1%).
- Customers with 2 products churn the least; those with 3+ products experience extreme churn (83–100%).
- Inactive clients have nearly double the churn rate compared to active ones.
- Financial factors like high-balance customers ($80K+) have slightly higher churn.

---

## Recommendations & Business Impact
- Target female and middle-aged customers with loyalty programs.
- Investigate and mitigate churn in the German market.
- Re-engage inactive clients with special offers.
- Optimize multi-product offerings to prevent extreme churn.
- Offer exclusive retention benefits to high-value clients.

---

## Data & Methodology
- **Data Source:** 
  - `data/churn_raw.csv` – Original dataset
  - `data/churn_clean.csv` – Cleaned and preprocessed dataset
- **SQL:**  
  - `sql/churn_cleaning.sql` – Data cleaning queries  
  - `sql/churn_exploratory.sql` – Exploratory analysis queries
- **Python:** Analysis and preprocessing scripts (python/)
- **Power BI:** Dashboard `dashboard/Bank Churn Analysis.pbix` visualizing demographic, behavioral, and financial insights

---

## Dashboard & Visuals
### Key Metrics
- Total Churn Rate
- Total Customers
- Total Churned Customers

### Selected Charts
![Churn by Age and Gender](images/chart1.png)  
![Churn by Products and Activity](images/chart2.png)  
![Churn by Balance and Salary](images/chart3.png)

---

## Deliverables
- SQL queries for data cleaning and exploratory analysis (`sql/`)
- Python scripts for preprocessing (`python/`)
- Power BI dashboard (`dashboard/Bank Churn Analysis.pbix`)
- Final Report (`report/Final_Report.pdf` and `report/Final_Report.docx`)
- Raw and cleaned data (`data/churn_raw.csv` and `data/churn_clean.csv`)
- Visuals for README (`images/`)
