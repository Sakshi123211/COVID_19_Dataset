# 🦠 COVID-19 Dynamics in India  
### Insights from an Excel Dashboard (March 2020 – August 2021)

## 📌 Project Overview
This project analyzes the **spread, testing, recovery, mortality, and vaccination trends of COVID-19 in India** using a structured **ETL pipeline, SQL-based data cleaning, and Excel-based analysis & dashboards**.

The goal of this project is to convert large, state-wise COVID-19 datasets into **clear insights and interactive dashboards** that support public-health analysis and data-driven decision making.

---

## 👩‍💻 Contribution
- **Type:** Team Project  
- **Author:** Sakshi Singh  

---

## 📊 Dataset
- **File:** `covid_summary_final.csv`  
- **Coverage:** March 2020 – August 2021  
- **Granularity:** Daily, State-wise (India)

### Key Fields:
- Confirmed cases  
- Deaths & recoveries  
- Daily new cases  
- Testing data (total samples, positives)  
- Vaccination data (first dose, second dose)  
- Positivity rate  
- Risk level  

---

## 🛠 Tools & Technologies
- **SQL (PostgreSQL)** – ETL & data cleaning  
- **Microsoft Excel** – Data analysis & dashboarding  
- **ETL Concepts** – Extract, Transform, Load  
- **Excel Functions & Pivot Tables**

---

## 🔄 PART 1: ETL (Extract, Transform, Load)
**A. Extract Phase**
- Created a structured SQL table with correct data types
- Loaded 80,000+ records covering all Indian states
- Verified date coverage and categorical consistency

**B. Transform Phase**
- Standardized state names and risk labels
- Handled missing and zero-value anomalies
- Calculated:
    - Case Fatality Rate (CFR)
    - Daily tests from cumulative samples
    - Lagged variables for correlation analysis
 
**C. Load Preparation**
- Created an analysis-ready table with:
    - Year extraction
    - Average yearly daily cases
    - Peak daily cases per state
    - Peak date identification
- Exported cleaned data for Excel analysis

--- 

## 📈 PART 2: Excel Data Analysis
**Key analytical tasks performed using Excel formulas, PivotTables, and filters:**
- Missing data handling
- Date normalization (dd-mm-yyyy)
- Daily new cases calculation
- State-wise case proportion
- Cumulative vaccination rate
- Merging case & testing data
- Average monthly cases
- Positivity rate calculation
- Age-group vaccination analysis
- Top 5 states by confirmed cases
- Month-wise case trends
- Weekday analysis of cases
- Vaccination vs recovery analysis
- Advanced filtering for high CFR states
- Time-series forecasting (30-day forecast)
- Conditional formatting for hotspots
- Risk assessment (High / Medium / Low)
- Total tests calculation
- Date-based queries using INDEX & MATCH
- State-specific analysis
- Data validation with dropdowns
- CFR trend analysis
- Correlation between testing & cases
-  Peak case day analysis

---

## 📊 PART 3: Excel Dashboard
The Excel dashboard includes:
- COVID-19 Case Summary Panel
  - Total cases, active cases, recoveries, deaths
- Vaccination Progress Tracker
  - Dose-wise and age-group analysis
- Testing Analysis Section
  - Total tests and positivity rates
- Trend Analysis
  - Cases, deaths, recoveries over time
- State-wise Impact Overview
  - Heatmaps and comparative charts
- Advanced Statistical Insights
  - CFR, correlations, risk indicators
- Interactive Controls
  - Slicers, dropdowns, timeline filters
 
---

## 🎯 Key Insights
- Second wave peak observed between April–May 2021
- Strong correlation between increased testing and detected cases
- Significant variation in CFR and recovery rates across states
- Vaccination rollout shows age-group prioritization trends
- Risk classification highlights high-burden states effectively

---

## 🚀 How to Use
- **Clone this repository:** git clone https://github.com/your-username/COVID-19-India-Analysis.git
- Open the Excel dashboard file
- Use slicers, filters, and dropdowns to explore insights

--- 

## 👩‍🎓 Author
**Sakshi Singh**
- 🎓 Data Science & AI | AlmaBetter (IIT Guwahati)
- 📊 Aspiring Data Analyst
- 🛠 Python | SQL | Excel | Power BI | Tableau
