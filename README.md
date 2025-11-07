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

### Demographics
- **Younger employees (<35)** have a higher attrition rate.  
- **Single employees** tend to leave more than married ones.  
- **Male employees** show slightly higher turnover.

### Job & Compensation
- **Lower Job Levels** and **lower Monthly Income** are strongly linked to attrition.  
- Employees working **Overtime** are more likely to leave.  
- **Shorter tenure** employees show higher attrition probability.

### Satisfaction & Work Environment
- **Low Job Satisfaction** and **poor Work-Life Balance** are top attrition drivers.  
- **Environment Satisfaction** and **Relationship Satisfaction** also correlate negatively with attrition.

---

## 🧩 Correlation Highlights

- `MonthlyIncome` ↔ `JobLevel` → **Strong Positive Correlation**  
- `Attrition` ↔ `YearsAtCompany`, `Age`, `JobSatisfaction` → **Negative Correlation**  
- `OverTime` ↔ `Attrition` → **Positive Correlation**

---

## 🧭 Recommendations

1. **Enhance Employee Engagement**
   - Conduct regular feedback surveys and act promptly.  
   - Recognize and reward top performers.

2. **Improve Work-Life Balance**
   - Limit mandatory overtime.  
   - Promote flexible or hybrid work options.

3. **Focus on Early-Career Retention**
   - Provide mentorship programs.  
   - Offer clear growth paths and training support.

4. **Leverage Predictive Analytics**
   - Use attrition models (e.g., Logistic Regression, Decision Trees) to flag high-risk employees.  
   - Target interventions for low-satisfaction departments.

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

## 🏁 Conclusion

This analysis reveals that **satisfaction, income, and workload** are the most influential factors driving attrition.  
By addressing these through **data-backed HR policies**, organizations can improve retention, reduce costs, and enhance employee well-being.  
The findings form a foundation for future predictive modeling and advanced analytics.

---

## 👩‍💻 Author
**Neethu K V**  
Data Analytics Enthusiast | HR Analytics Explorer  
📧 *[neethu702@gmail.com]*

---

⭐ *If you found this project helpful, give it a star on GitHub!*

