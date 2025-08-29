# HR Analytics Dashboard (Employee Attrition)  

This project is an **interactive HR Analytics Dashboard** built in **Power BI** using the IBM HR Analytics dataset (~1,470 employee records).  
The goal was to analyze **employee attrition patterns** and provide **data-driven insights** to support HR in improving retention strategies.  

---

## Dashboard Overview  

The dashboard is divided into **3 pages**:  

### 1. **Overview**  
- KPIs: Total Employees, Employees Left, Attrition Rate %, Avg Monthly Income, Avg Tenure.  
- Department-wise attrition (counts + attrition rate %).  
- Attrition by Age Band and Gender.  
- Slicers for Job Role and Education Field.  

### 2. **Compensation & Workload**  
- Attrition by Salary Band and Tenure Band.  
- Overtime vs Attrition (Yes/No).  
- Average salary comparison between employees who stayed vs left.  
- Slicers for Department and Job Role.  

### 3. **Engagement & Risk**  
- Attrition by Job Satisfaction and Work-Life Balance.  
- Attrition trend across Years at Company.  
- High-risk roles table (conditional formatting on Attrition Rate %).  

---

## Key Features  

- Created **calculated columns** for Age, Tenure, and Income Bands.  
- Built **DAX measures** for Attrition Rate %, Employees Left, Avg Salary, Avg Tenure.  
- Used **line & clustered column charts, slicers, cards, and conditional formatting** for interactivity.  
- Delivered actionable insights such as:  
  - **Early-tenure employees (0–1 years)** have the highest attrition (~35%).  
  - **Sales Representatives** face ~40% attrition (highest-risk role).  
  - **Employees with overtime** leave at nearly 2x the rate of those without.  
  - **Lower income bands (<3K)** show significantly higher turnover.  

---

## Business Impact  

This dashboard helps HR teams:  
- Identify **high-risk employee groups** (by role, department, salary band, tenure).  
- Understand **compensation and workload factors** driving attrition.  
- Take **targeted actions** such as onboarding improvements, workload balancing, and compensation adjustments.  

---

- Dataset: [IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)  
