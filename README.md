# 🧠 HR Analytics Power BI Dashboard
A sleek, interactive Power BI dashboard visualizing employee demographics, tenure, satisfaction, and work-life balance.

## 📊 Key Features
- **KPIs:** Total Employees, Attrition Rate, Average Age, Average Tenure
- **Visuals:** Attrition by Education, Job Role Distribution, Attrition by Age, Average Tenure by Role, Satisfaction Score, Work-Life Balance by Department
- **Slicers:** Department, Gender

## 🧹 Data Workflow
- **Source:** [Simulated HR Employee Dataset](https://www.kaggle.com/datasets/rhuebner/human-resources-data-set)  
- **Cleaned using:** Excel (added `AttritionFlag` using `=IF([@Attrition]="Yes",1,0)`; grouped Tenure, Age, and Salary)
- **Visualized in:** Power BI Web (gray-blue theme with KPI cards and interactive slicers)

## 📈 Insights
- Overall attrition rate of **16.1%**
- **Younger employees (<30)** show the highest attrition
- **Managers** and **research roles** have the longest tenure
- **Work-life balance** and **satisfaction** are steady across departments
- **Life Sciences** background dominates the employee base

## 🧰 Tools Used
Power BI (Web) · Excel · Data Modeling · DAX · Dashboard Design · Visualization
