# Data Analytics - Level 1: Data Cleaning & Exploratory Data Analysis

## 1. Project Overview

This project focuses on cleaning and analyzing an employee dataset to understand workforce characteristics, compensation patterns, employee performance, hiring activity, and work arrangements.

The project follows a practical data analytics workflow:

**Data Cleaning → Data Validation → Exploratory Data Analysis → Visualization → Business Insights**

The analysis was performed using Python and data analytics libraries in Jupyter Notebook.

---

## 2. Objectives

The main objectives of this project are to:

- Understand the structure and characteristics of the employee dataset.
- Identify and handle data quality issues.
- Prepare a clean and analysis-ready dataset.
- Explore workforce distribution across departments and regions.
- Analyze employee salary patterns.
- Examine employee performance categories.
- Understand remote and non-remote workforce distribution.
- Analyze employee hiring activity across different years.
- Identify meaningful business insights from the data.

---

## 3. Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- VS Code
- Git & GitHub

---

## 4. Project Structure

```text
DataAnalytics-L1-CleaningData/
│
├── dataset/
│   └── Messy_Employee_dataset.csv
│
├── notebooks/
│   ├── Data_Cleaning.ipynb
│   └── EDA.ipynb
│
├── outputs/
│   └── cleaned_employee_dataset.csv
│
├── README.md
└── requirements.txt
```

---

# 5. Data Cleaning

The raw employee dataset was systematically examined and transformed into a clean, analysis-ready dataset.

The data cleaning process included:

- Loading and inspecting the dataset.
- Examining the dataset structure and information.
- Generating a data quality report.
- Checking missing values.
- Identifying duplicate records.
- Checking numeric columns for possible range anomalies.
- Handling missing data using appropriate strategies.
- Removing duplicate records where applicable.
- Standardizing categorical and text formatting.
- Removing leading and trailing spaces.
- Standardizing department and region values.
- Converting the `Join_Date` column from text to datetime format.
- Detecting numeric outliers using the IQR method.
- Assessing and documenting outlier treatment.
- Correcting data types.
- Performing final data validation.
- Comparing the dataset before and after cleaning.
- Saving the cleaned dataset as a new CSV file.

### Cleaning Results

The before-and-after validation showed:

| Metric | Before Cleaning | After Cleaning |
|---|---:|---:|
| Row Count | 1,020 | 1,020 |
| Total Missing Values | 235 | 0 |
| Duplicate Rows | 0 | 0 |
| Correct Data Types | 10/12 | 12/12 |

The final validation confirmed that the cleaned dataset was ready for further analysis.

The complete cleaning process is documented in:

`notebooks/Data_Cleaning.ipynb`

---

# 6. Exploratory Data Analysis

The cleaned employee dataset was used for Exploratory Data Analysis to identify workforce patterns and business insights.

The complete analysis is documented in:

`notebooks/EDA.ipynb`

## 6.1 Dataset Overview

The cleaned dataset contains **1,020 employee records and 12 columns**.

The dataset was initially explored to understand its structure, available fields, and overall characteristics.

---

## 6.2 Dataset Profiling

The dataset was profiled using descriptive statistics and data-type information to understand the numerical and categorical variables.

This provided the foundation for the subsequent workforce, salary, performance, and hiring analyses.

---

## 6.3 Workforce Distribution

Employee distribution was examined across department and region combinations.

This analysis helps understand how employees are distributed throughout the organization and identifies workforce concentration across different segments.

A visualization was created to highlight the top department-region combinations by employee count.

---

## 6.4 Employee Performance Analysis

Employee counts were analyzed across different performance categories:

- Good
- Average
- Excellent
- Poor

The analysis helps understand the overall distribution of employee performance levels across the workforce.

A visualization was created to compare the number of employees in each performance category.

---

## 6.5 Salary Analysis

Employee salary data was analyzed to understand overall compensation levels.

The analysis included:

- Average salary
- Median salary
- Minimum salary
- Maximum salary
- Salary distribution

The salary distribution was visualized using a histogram to understand how employee salaries are spread across the workforce.

The analysis showed an average salary of approximately **85,164**, with a median salary of approximately **85,548**.

---

## 6.6 Average Salary by Department and Region

Average salary was compared across department-region combinations.

The analysis identified differences in average compensation across different workforce segments.

The top department-region combinations by average salary included:

- Admin - Illinois
- Cloud Tech - Florida
- Sales - Florida
- DevOps - Nevada
- Admin - California
- Finance - New York
- Sales - California
- HR - Texas
- HR - California
- HR - Illinois

This analysis can support compensation analysis, budgeting, and workforce planning.

---

## 6.7 Remote Work Analysis

The distribution of employees working remotely and non-remotely was analyzed.

The results show that the workforce is almost evenly divided between remote and non-remote employees, indicating a relatively balanced work model.

This analysis can help organizations understand the overall distribution of work arrangements.

---

## 6.8 Hiring Activity Analysis

Employee hiring activity was analyzed using employee joining years.

The analysis showed variations in hiring activity across the years, with the highest hiring activity occurring in **2023** and the lowest in **2022**.

This provides an overview of changes in recruitment activity over time and can support workforce and recruitment planning.

---

# 7. Key Business Insights

The analysis produced the following key findings:

- The workforce is almost evenly divided between remote and non-remote employees, indicating a balanced work model.
- Good, Average, and Excellent performance categories have similar employee counts, while the Poor category has fewer employees.
- Hiring activity was highest in 2023 and lowest in 2022, indicating variations in recruitment activity across the years.
- Workforce distribution varies across department-region combinations, highlighting differences in employee concentration.
- Average salary differs across department-region combinations, indicating variations in compensation levels across workforce segments.

These insights can support:

- Workforce planning
- Compensation analysis
- Recruitment planning
- Budgeting
- Management decision-making

---

# 8. Visualizations

The project includes visualizations for:

- Workforce distribution
- Salary distribution
- Average salary by department and region
- Employee performance distribution
- Remote work distribution
- Employee hiring activity by year

The project visualizations are stored in the `Images` folder.

---

# 9. Output

The cleaned dataset generated during the data preparation stage is stored in:

`outputs/cleaned_employee_dataset.csv`

The cleaned dataset is used as the input for the Exploratory Data Analysis notebook.

---

# 10. How to Run the Project

1. Clone or download the repository.
2. Open the project folder in VS Code or Jupyter Notebook.
3. Install the required Python libraries using:

```bash
pip install -r requirements.txt
```

4. Open and run:

```text
notebooks/Data_Cleaning.ipynb
```

5. The cleaned dataset will be generated in the `outputs` folder.
6. Then open and run:

```text
notebooks/EDA.ipynb
```

7. The EDA notebook uses the cleaned dataset to reproduce the analysis and visualizations.

---

# 11. Conclusion

This project demonstrates an end-to-end introductory data analytics workflow, starting with data cleaning and validation and progressing to exploratory analysis, visualization, and business insight generation.

The analysis demonstrates how employee data can be transformed into meaningful information for understanding workforce structure, compensation, performance, recruitment activity, and work arrangements.

The project also demonstrates the importance of data quality and validation before performing business analysis.

---

# 12. Project Status

**Completed**

- Data Cleaning: ✅
- Data Validation: ✅
- Cleaned Dataset: ✅
- Exploratory Data Analysis: ✅
- Data Visualizations: ✅
- Business Insights: ✅
- README Documentation: ✅