# Healthcare Readmission Analytics

An end-to-end healthcare analytics project analyzing hospital readmissions using Python, PostgreSQL, and Power BI.

---

## Project Objective

To identify high-risk patient segments, analyze clinical and operational drivers of readmissions, and provide data-driven business recommendations to reduce readmission rates and financial impact.

---

## Tech Stack

- Python (Data Cleaning & Transformation)
- PostgreSQL (SQL Data Layer)
- Power BI (Dashboard & Visualization)
- Git & GitHub (Version Control)

---

## Project Workflow

### Phase 1: Data Cleaning (Python)
- Cleaned raw hospital dataset
- Handled missing values and inconsistencies
- Created flags: `readmitted_flag`, `circulatory_flag`, `injury_flag`
- Exported cleaned CSV for SQL ingestion

### Phase 2: SQL Data Modeling (PostgreSQL)
- Created structured database table
- Imported cleaned dataset
- Performed aggregation queries
- Validated readmission counts and distributions

### Phase 3: Power BI Dashboard
Developed a 4-page interactive dashboard:

1. Executive Overview  
2. Clinical & Risk Analysis  
3. Operational Insights  
4. Business Insights & Recommendations  

Created DAX measures including:
- Total Patients  
- Total Readmitted Patients  
- Readmission Rate %  
- High Risk Readmission %  
- Avg Time in Hospital  
- Estimated Cost per Patient  
- Highest Risk Tier  

---

## Key Insights

- Very High risk tier contributes the highest readmissions
- Extended length of stay increases financial burden
- Diagnosis severity strongly impacts readmission probability
- Risk tier directly correlates with readmission rate

---

## Business Recommendations

- Focus intervention on Very High risk tier
- Reduce extended length-of-stay cases
- Implement diagnosis-specific monitoring
- Proactive follow-up for high-risk patients

---

## Project Structure

```
data/
    hospital_readmission_cleaned.csv

sql/
    schema.sql
    analysis_queries.sql

powerbi/
    Healthcare_Readmission_Analytics.pbix
```

---

## Conclusion

This project demonstrates end-to-end data analytics capability:

- Data Cleaning (Python)
- SQL Modeling (PostgreSQL)
- BI Dashboard Development (Power BI)
- Executive-Level Storytelling


