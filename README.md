# 🏢 Louisville Metro Employee Payroll & Overtime Analysis

Uncovering salary patterns, overtime concentration, and departmental payroll drivers.

A data-driven analysis of **40,829 employee payroll records** from Louisville Metro Government to identify compensation trends, overtime dependency, and actionable workforce recommendations.

---

## 📊 Project Overview

### 🚨 The Problem  
Large public-sector organizations must manage payroll spending efficiently while ensuring fair compensation and controlling overtime costs.

---

### 🔍 The Focus  
This project aims to understand:

- Which departments contribute most to payroll expenditure  
- Where overtime costs are most concentrated  
- What salary patterns and anomalies exist across job roles  

---

### 💡 The Insight  
Employee compensation is strongly influenced by **departmental structure, job roles, and overtime practices**, with significant outliers impacting total payroll costs.

---

## 💡 Key Findings

### 1. Salary Distribution is Highly Uneven  
- `Annual_Rate` values vary widely across employees  
- Most employees fall within a moderate salary range  
- A small number of roles earn extremely high salaries  

📌 **Takeaway:** Salary distribution is **right-skewed**, reflecting senior or specialized positions.

---

### 2. Overtime Pay is Concentrated in Specific Departments  
- Overtime compensation differs greatly across departments  
- Certain operational departments consistently show higher overtime rates  

📌 **Takeaway:** Overtime is not evenly spread — it is driven by workload and staffing needs.

---

### 3. Department-Level Payroll Differences are Significant  
- Some departments have the highest average annual salaries  
- Others rely more heavily on overtime pay rather than base salary  

📌 **Takeaway:** Payroll structure varies depending on departmental responsibilities.

---

### 4. Annual Salary vs Overtime Shows a Weak Relationship  
- Employees with lower base salaries often receive higher overtime  
- High-salary employees tend to receive less overtime compensation  

📌 **Takeaway:** Overtime contributes more to earnings for mid-to-lower salary employees.

---

### 5. Outliers Strongly Impact Payroll Spending  
- Extremely high values in `Annual_Rate`, `Overtime_Rate`, and `YTD_Total` were observed  
- These may represent executive roles, specialized jobs, or exceptional overtime workloads  

📌 **Takeaway:** Outlier investigation is essential for accurate budgeting and compliance.

---

## 🛠️ Tools & Technologies

- Python 3.9+ – Data analysis  
- Pandas – Cleaning and manipulation  
- Matplotlib – Visualizations  
- Jupyter Notebook – Reporting and insights  

---

## 🎯 Top Recommendations

✅ Monitor departments with consistently high overtime for staffing improvements  
✅ Review extreme salary and overtime outliers for auditing and transparency  
✅ Perform deeper job-title-based compensation analysis  
✅ Use predictive modeling to forecast overtime and payroll budgets  
✅ Optimize workforce allocation to reduce overtime dependency  

---

## 📊 Dataset Information

- **Source:** Louisville Metro KY Employee Salary Data  
- **Size:** 40,816 payroll records  
- **Features (11):** Department, Job Title, Annual Rate, Regular Rate, Overtime Rate, Incentives, YTD Total  
- **Time Period:** Calendar year-based payroll snapshot (`CalYear`)  

---

## ⭐ Final Summary

This project successfully identified key salary structures, overtime concentration, departmental payroll variation, and compensation outliers within Louisville Metro’s workforce. These findings support improved workforce planning, payroll transparency, and cost optimization strategies





