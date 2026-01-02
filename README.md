# 📘 Pandemic Patterns: COVID-19 Dynamics in India

End-to-End Data Analytics Project (SQL + Excel Dashboard)

# 🔍 Project Overview

The COVID-19 pandemic generated massive, complex datasets across cases, testing, and vaccination metrics.
This project demonstrates an end-to-end data analytics workflow where raw healthcare data is transformed into actionable insights using SQL for ETL and Excel for analysis and dashboarding.

The goal is to showcase real-world data handling, analytics thinking, and business-ready reporting, making this project highly relevant for Data Analyst / Business Analyst / Healthcare Analytics roles.

# 🎯 Objectives

* Perform ETL (Extract, Transform, Load) on raw COVID-19 datasets using SQL

* Standardize and clean multi-source healthcare data

* Generate meaningful KPIs such as:

  * Daily New Cases

  * Case Fatality Rate (CFR)

  * Positive Testing Rate

  * Vaccination Coverage

* Build an interactive Excel dashboard for data storytelling

* Derive insights and recommendations for public health decision-making

# 🗂️ Datasets Used

Dataset	Description

covid_19_india.csv	State-wise daily COVID cases, recoveries, and deaths

covid_vaccine_statewise.csv	Vaccination progress by state

StatewiseTestingDetails.csv	COVID testing statistics

# 🛠️ Tech Stack & Tools

* SQL (SQLite) – Data cleaning, transformations, joins, aggregations

* Python (Pandas) – Data loading and SQL integration

* Excel – Analysis, PivotTables, charts, forecasting, dashboard

* Google Colab – SQL ETL execution environment

# 🔄 ETL Process (SQL)

# Extract

* Loaded all datasets into a SQL database using Pandas

# Transform

* Key transformations performed:

* Standardized date formats across datasets

* Cleaned and normalized state names

  * Calculated:

  * Daily New Cases (using LAG)

  * Case Fatality Rate (CFR)

  * Positive Testing Rate

* Merged cases + testing + vaccination data

* Created analytical tables:

  * vacc_clean

  * covid_summary

# Load

* Exported final analytical dataset as:

  covid_summary.csv

* Used for Excel-based analysis and dashboard creation


# 📊 Excel Analysis & Dashboard

Key Analyses

* Daily & cumulative case trends

* State-wise case distribution

* Testing efficiency & positive rate analysis

* Vaccination progress (First Dose vs Second Dose)

* Risk classification (High / Medium / Low)

* Month-wise & weekday trends

* Time-series forecasting using FORECAST.ETS

* Correlation between testing and positive cases

# Dashboard Features

* Interactive slicers (State, Date)

* Line charts for trend analysis

* Bar & clustered bar charts for comparisons

* Clean, business-ready visual design

# 📂 Excel File:

Covid_Summary_Final.xlsx

# 📌 Key Insights

* Uneven State Impact: Maharashtra, Kerala, and Karnataka consistently showed higher case volumes

* Vaccination Effectiveness: Fatality rates declined post-vaccination rollout

* Testing Matters: Higher testing correlated with better detection and control

* Hidden Risk: Some states showed high positive rates despite moderate testing

* Risk Reduction Over Time: High-risk states reduced as vaccination coverage improved

# ✅ Business Recommendations

* Increase testing in states with high positivity rates

* Strengthen vaccination drives in low-coverage regions

* Use early trend detection for proactive healthcare planning

* Maintain robust data pipelines for future outbreaks

# 🧠 Learning Outcomes

* Hands-on experience with SQL-based ETL pipelines

* Advanced Excel skills (PivotTables, dashboards, forecasting)

* Improved data storytelling and stakeholder-ready reporting

* Real-world healthcare analytics exposure

# 👤 About the Author

Name: Tauseef Alam

Program: DS Excel Analytics

Role Target: Data Analyst | Business Analyst | Healthcare Analyst

# Dashboard 1:
<img width="1698" height="1132" alt="Dashboards01" src="https://github.com/user-attachments/assets/0e725374-143e-410e-a0d1-f79e5628981d" />

# Dashboard 2:
<img width="1801" height="1176" alt="Dashboards02" src="https://github.com/user-attachments/assets/232bb899-5acd-47a9-8b44-9fc46197b007" />
