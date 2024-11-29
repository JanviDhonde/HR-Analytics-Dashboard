## 📊 HR Analytics Dashboard - 2024  

### 📜 Project Overview  
The **HR Analytics Dashboard** is a dynamic and interactive Power BI project designed to analyze and monitor key HR metrics, such as attrition rate, job satisfaction, and workforce demographics. This dashboard enables HR professionals to make informed, data-driven decisions to enhance employee retention, satisfaction, and overall workforce management.  

### ✨ Objective  
The primary objectives of this project are:  
- To provide actionable insights into employee attrition patterns and workforce demographics.  
- To analyze job satisfaction trends across departments and roles.  
- To help HR teams identify and address areas contributing to employee turnover.  

### 🔍 Key Insights and Features  

#### **1. Key Metrics**  
- **Attrition Count**: 237 employees  
- **Total Employee Count**: 1,470  
- **Attrition Rate**: 16.1%  
- **Average Salary**: ₹6.5K  
- **Average Age**: 37 years  
- **Average Tenure**: 7 years  

#### **2. Attrition Analysis**  
- **By Education**: Medical (27%) and Life Sciences (38%) have the highest attrition rates.  
- **By Job Role**: Sales Executives and Laboratory Technicians experience the most attrition.  
- **By Salary Slab**: Employees earning less than ₹5K contribute to 68.7% of total attrition.  
- **By Gender**: Male (140) and Female (79).  

#### **3. Job Satisfaction**  
- Highest satisfaction (Level 4) observed in roles such as Research Scientist and Lab Technician.  

#### **4. Department-Wise Insights**  
- Departments like **Human Resources** and **Sales** have higher attrition compared to others.  



### 🛠️ Tools and Technologies Used  
- **Power BI**: To design and develop the dashboard.  
- **DAX (Data Analysis Expressions)**: To calculate advanced metrics like attrition rate, averages, and more.  
- **Data Sources**: Processed HR datasets in Excel, SQL, or CSV formats.  


### 📊 Dashboard Visualizations  
The dashboard includes the following features:  
1. **Key Metrics Tiles**: Overview of attrition, employee count, and averages.  
2. **Pie Chart**: Attrition distribution by education level.  
3. **Bar Charts**: Attrition breakdown by job role, salary slab, and gender.  
4. **Line Chart**: Attrition trends by years at the company.  
5. **Matrix Visualization**: Job satisfaction levels by role.  


### 📈 Project Learnings  
This project highlights:  
- Advanced Power BI features like slicers, filters, and drill-downs for in-depth analysis.  
- Effective data modeling using calculated measures and columns.  
- The importance of visually representing HR data to enhance decision-making.  


### 📂 How to Use the Dashboard  

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/your-username/hr-analytics-dashboard.git
   ```
2. **Open in Power BI Desktop**: Load the `.pbix` file.  
3. **Interact with the Dashboard**: Use slicers and filters to analyze specific metrics like department, job role, and gender.  


### Key DAX Measures  
#### Attrition Rate  
```DAX
AttritionRate = SUM(HR_Analytics[AttritionCount]) / SUM(HR_Analytics[EmployeeCount])
```

#### Average Tenure  
```DAX
AverageTenure = AVERAGE(HR_Analytics[YearsAtCompany])
```

### 📊 Dashboard Preview  
![HR Analytics Dashboard](HR%20Analytics%20Dashboard.png)  

### 🌟 Why This Project Matters  
This dashboard transforms raw HR data into actionable insights, enabling organizations to:  
- Identify trends and areas driving high attrition.  
- Improve workforce satisfaction through targeted interventions.  
- Support data-driven HR planning and policy formulation.  

### ⭐ Feedback  
If you found this project helpful, consider ⭐ this repository and sharing your feedback! 😊  
