# IBM-HR-Analytics-Employee-Attrition-Performance
Data Analytics - Final Project
# 🧠 Employee Attrition Analysis (EDA)

**Dataset:** [IBM HR Analytics Employee Attrition & Performance](https://www.google.com/url?q=https%3A%2F%2Fexcelbianalytics.com%2Fwp%2Fdownloads-21-sample-csv-files-data-sets-for-testing-till-5-million-records-hr-analytics-for-attrition%2F)  
**Project Type:** Exploratory Data Analysis (EDA)  
**Toolset:** Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook  

---

## 📊 Project Overview

Employee attrition (or turnover) is a critical issue for organizations as it impacts productivity, recruitment costs, and morale.  
This project explores employee data to identify **factors influencing attrition** and provides **data-driven insights** to support HR retention strategies.

---

## 🎯 Objectives

- Analyze employee demographics, work patterns, and satisfaction scores.  
- Identify correlations and trends associated with employee turnover.  
- Visualize data to reveal hidden patterns influencing attrition.  
- Provide actionable insights and HR recommendations to improve retention.

---

## 💾 Dataset Description

**Dataset Name:** *IBM HR Analytics Employee Attrition & Performance*  
**Rows:** 1,470  
**Columns:** 35  

### Key Columns
| Feature | Description |
|----------|--------------|
| `Age` | Age of the employee |
| `Attrition` | Whether the employee left the company (Yes/No) |
| `BusinessTravel` | Frequency of business travel |
| `Department` | Department of the employee |
| `DistanceFromHome` | Distance from home to workplace |
| `Education` | Education level (1–5) |
| `EnvironmentSatisfaction` | Satisfaction with workplace environment |
| `JobSatisfaction` | Level of job satisfaction |
| `MonthlyIncome` | Monthly salary |
| `OverTime` | Whether the employee works overtime |
| `YearsAtCompany` | Total years spent in the company |

---

## 🔍 Exploratory Questions

| Question | Purpose |
|-----------|----------|
| What is the overall attrition rate? | Understand the scale of turnover. |
| Does age or gender influence attrition? | Identify demographic patterns. |
| Does salary or job level affect attrition? | Explore financial motivators. |
| How do satisfaction levels relate to attrition? | Assess employee engagement. |
| Is overtime linked to higher attrition? | Analyze workload effects. |
| Which features are most correlated with attrition? | Identify top predictors. |

---

## 📈 Key Visualizations

| Visualization | Purpose |
|----------------|----------|
| Countplot | Show attrition distribution across categories. |
| Bar Chart | Compare attrition across departments or satisfaction scores. |
| Histogram | Display age and tenure distributions. |
| Box Plot | Compare income and distance across attrition status. |
| Heatmap | Show correlation between numeric features. |
| Pie Chart | Illustrate overtime or attrition proportions. |
| Pairplot | Explore relationships between numeric variables. |

---

## 💡 Insights

### 1. Key Attrition Trends
- **Overall Attrition Rate:** Around *16%–20%* of employees have left the organization, indicating a moderate turnover level that warrants attention.
- **Departmental Impact:** The **Sales** and **Human Resources** departments experience higher attrition compared to **Research & Development (R&D)**. This suggests potential issues related to job pressure, incentives, or career growth in these teams.
- **Job Role Sensitivity:** **Laboratory Technicians, Sales Executives, and Human Resources roles** show the highest attrition levels — likely due to workload imbalance, limited progression, or external job opportunities.

### 2. Demographic Insights
- **Age Group:** Attrition is higher among employees aged **25–35 years**, representing early-career professionals who often explore better prospects.
- **Marital Status:** **Single employees** show a notably higher attrition rate, possibly due to mobility and flexibility to switch jobs.
- **Gender:** **Male attrition** is slightly higher than female attrition, potentially linked to departmental distributions or role expectations.

### 3. Job-Related Insights
- **Years at Company:** Employees with **<3 years of experience** at the company are more likely to leave, suggesting onboarding or early engagement issues.
- **Years in Current Role:** Attrition peaks among those in the same role for **2–5 years**, hinting at stagnation or lack of promotion opportunities.
- **OverTime:** A strong positive correlation exists between **OverTime and Attrition** — employees working frequent overtime hours are more likely to leave, likely due to burnout or work-life imbalance.
- **Job Satisfaction:** Lower satisfaction levels strongly correlate with attrition. Retention strategies should focus on improving role clarity, recognition, and work environment.

### 4. Compensation & Performance
- **Monthly Income:** Lower-income employees show **significantly higher attrition**, suggesting dissatisfaction with compensation or market competitiveness.
- **Stock Options & Benefits:** Employees with **no stock options** or lower benefit levels have higher attrition — financial incentives play a critical retention role.
- **Performance Rating:** No strong direct relationship observed between performance rating and attrition, implying that high performers may also be leaving — a concerning sign for talent retention.

### 5. Work Environment & Balance
- **Work-Life Balance:** Employees rating this factor as “Poor” or “Fair” have a much higher likelihood of leaving the organization.
- **Environment Satisfaction:** Teams with low environmental satisfaction (e.g., management support, resources, or interpersonal relations) exhibit higher turnover.

### 6. Key Drivers of Attrition
| Rank | Factor | Influence on Attrition |
|------|---------|------------------------|
| 1 | OverTime | Strong positive correlation |
| 2 | Monthly Income | Lower income → higher attrition |
| 3 | Years at Company | New employees leave more |
| 4 | Job Satisfaction | Lower satisfaction → higher attrition |
| 5 | Work-Life Balance | Poor balance → higher attrition |

### 7. Recommendations
- **Implement Early Retention Programs:** Focus on employees in their first 2 years with mentoring and career growth paths.
- **Optimize Workload Distribution:** Reduce overtime frequency through better resource planning.
- **Review Compensation Structures:** Ensure salaries are competitive for high-turnover roles, especially in Sales and HR.
- **Enhance Career Progression:** Introduce internal mobility and skill development programs.
- **Promote Work-Life Balance:** Encourage flexible hours or hybrid work models where possible.
- **Monitor High-Risk Groups:** Continuously track attrition patterns among young, single, and low-income employees.

---

### Conclusion
Employee attrition in this dataset is primarily driven by **workload pressure, compensation dissatisfaction, limited career growth, and early disengagement**. Addressing these through **targeted retention, rewards, and engagement initiatives** can significantly reduce turnover and enhance organizational stability.

---

## 🧰 Tech Stack

- **Language:** Python 3.x  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **IDE:** Jupyter Notebook  
- **Dataset Source:** ExcelDataAnalytics.com  

---

## 📎 Files Included

| File | Description |
|------|--------------|
| `IBM_HR_Attrition_Analysis.ipynb` | Main notebook containing all Summary of Insights , EDA steps and visualizations |
| `README.md` | Project documentation |
| `HR-Employee-Attrition.csv/` | Dataset files |

---



## 👩‍💻 Author
**Neethu K V**  
Aspiring Data Analyst | HR Analytics Explorer  
📧 *[neethu702@gmail.com]*

---

⭐ *If you found this project helpful, give it a star on GitHub!*

