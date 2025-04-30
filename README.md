# loan-dashboard-project

# Loan Dashboard Project

This project analyzes loan applicant data to uncover insights that can help financial institutions make data-driven decisions on loan approvals. The analysis spans applicant demographics, financial profiles, credit history, and loan status, culminating in an interactive dashboard built in Power BI.

## Objective

To identify patterns in loan approval likelihood based on applicant attributes and financial behaviors. The project answers key business questions, such as:
- What factors influence loan approval rates?
- Which demographic groups have higher approval success?
- How do income and loan amounts vary by education, employment, and region?

---

## Tools Used
- **SQL (Oracle SQL Developer)** – Data exploration and aggregation
- **Python (Google Colab)** – Data preprocessing, cleaning, and exploratory data analysis
- **Power BI** – Interactive dashboard creation and visualization
- **GitHub** – Version control and project publishing

---

## Key Insights
- Applicants with a **credit history** had significantly higher approval rates.
- **Semiurban regions** had the highest approval percentages.
- **Female applicants** showed slightly higher approval rates in certain regions.
- Most common **loan term** was 360 months.
- Average applicant income was around **$5,000**, with median loan amounts around **$130**.

---

## Repository Structure

| File | Description |
|------|-------------|
| `Loan2P.sql` | SQL queries used for analysis (joins, aggregations, insights) |
| `loan_project.ipynb` | Google Colab notebook for Python-based cleaning and exploration |
| `loan_case.csv` / `loan_status.csv` | Raw Kaggle data files |
| `loan_case_cleaned.csv` / `loan_status_cleaned.csv` | Cleaned CSVs used in Power BI |
| `loan_dashboard.pbix` | Power BI file (open in Power BI Desktop) |
| `loan_dashboard.pdf` | Static PDF export of final dashboard |
| `README.md` | Project summary and documentation |

---

## Dashboard Overview

The Power BI dashboard includes:
1. **Loan Insights Overview** – Approval rates by gender, property area, and credit history
2. **Applicant Financials** – Income distribution, average loan amount, salary estimates
3. **Business Challenge Slide** – A mock scenario solved using visual analytics
4. **Summary Slide** – Final recommendations and takeaways

---

## How to Explore the Project

1. Clone the repository or download the files.
2. Open `loan_project.ipynb` in [Google Colab](https://colab.research.google.com) to explore the Python pipeline.
3. Use `Loan2P.sql` in Oracle SQL Developer to view all original SQL queries.
4. Open `loan_dashboard.pbix` in Power BI Desktop to explore the interactive dashboard.

---

## Data Source

- The dataset used was sourced from [Kaggle - Loan Prediction Dataset](https://www.kaggle.com/datasets/ajay1735/hloan-data-set). It includes 600+ rows of loan application data across demographics, employment, and loan status fields.

---

## Author

**Dionte Capleton**  
*Aspiring Data Analyst | SQL, Python, Power BI*


