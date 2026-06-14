# HR Employee Attrition Analysis

## Overview
Analyzed IBM HR Analytics data (1,470 employees, 35 features) to identify
why employees leave and which groups are at highest attrition risk.
Delivered 5 data-backed HR recommendations.

**Tools:** Python, Pandas, Matplotlib, Seaborn, SQL, Tableau

---

## Key Findings

- Sales department attrition (XX%) is Xx higher than R&D (XX%)
- Overtime employees are Xx more likely to quit than non-overtime employees
- Employees aged 30 and under have a XX% attrition rate vs XX% for 45+
- Churned employees earned $X,XXX/month vs $X,XXX for retained employees
- Attrition peaks at year X of tenure — the highest-risk onboarding window

---

## Visualizations

### 1. Attrition by Department
![Department Attrition](viz1_dept_attrition.png)

### 2. Monthly Income vs Attrition
![Income vs Attrition](viz2_income_attrition.png)

### 3. Overtime Impact
![Overtime Attrition](viz3_overtime_attrition.png)

### 4. Age Distribution
![Age Distribution](viz4_age_distribution.png)

### 5. Years at Company
![Years at Company](viz5_years_company.png)

### 6. Correlation Heatmap
![Correlation Heatmap](viz6_heatmap.png)

---

## Business Recommendations

1. **Sales retention is critical** — attrition XX% vs industry avg 10-15%
2. **Cap mandatory overtime** — overtime employees are Xx more likely to leave
3. **Invest in 0-2 year onboarding** — XX% churn in first 2 years
4. **Salary benchmarking** — bottom 25% earners drive disproportionate attrition
5. **Young talent program** — employees under 30 need structured growth paths

---

## Project Structure
| File | Description |
|------|-------------|
| `HR_Attrition_EDA.ipynb` | Full analysis notebook with all visualizations |
| `WA_Fn-UseC_-HR-Employee-Attrition.csv` | Dataset |
| `viz1` to `viz6` `.png` | Individual chart exports |