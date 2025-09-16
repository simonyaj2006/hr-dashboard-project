# hr-dashboard-project

Welcome to the HR Analytics Tableau Project repository! This project demonstrates how to build a complete end-to-end HR analytics solution, from raw HR data pre-processing to the creation of interactive Tableau dashboards. Designed  as a portfolio project, it reflects industry practices in  data analytics, visualization, and business intelligence. 

---

## Data Architecture

Although this project is focused on Tableau, it still follows a simplified pipeline approach:

1. **Source Data**: HR dataset (CSV/Excel file) containing employee  demographic, job role, and attrition information.
2. **Data  cleaning**: Performed using Excel/SQL (handling nulls, duplicates, and standardizing values).
3. **Data Modeling**: Creating relationships between employee attributes and fact tables.
4. **Visualization Layer**: Tableau dashboards built from the cleaned HR dataset.

---

## Project Overview

The HR Analytics Project is focused on employee data analysis to help HR teams improve decision-making and understand key workforce trends.

This Project involves: 

1.  **Data Collection & preparation**: Cleaning and transforming HR datasets (employee details, performance, attrition, salaries).
2.  **Data Modeling**: Structuring HR data into a format optimized for analysis.
3.  **Visualization**: Developing an interactive  HR dashboard in Tableau.
4.  **Innsights**: Providing actionable analytics on employee attrition, diversity, performance, and compensation trends.

This repository is a great resource for professionals and students to showcase expertise in: 
- Data Preparation (Excel/SQL/CSV cleaning)
- Business Intelligence Tools (Tableau)
- HR Metrics & KPIs
- Storytelling with Data

---

##  Important Tools & Technologies:

- **Tableau Public** – Data visualization and dashboards  
- **Excel / SQL** – Data cleaning and preparation  
- **GitHub** – Version control and portfolio showcase  
- **DrawIO** – For process flow and dashboard design mockups

---

## User Story - HR Dashboard

As an HR manager, I want a comprehensive dashboard to analyze human resources data, providing both summary views for high-level insights and detailed employee records for in-depth analysis

### Summary View

The summary view should be divided into three main sections: Overview, Demographics, and Income Analysis

#### Overview 

The Overview section should provide a snapshot of the overall HR Metrics, including:

- Display the total number of hired employees, active employees, and terminated employees.
- Visualize the total number of hired and terminated employees over the years.
- Present a breakdown of total employees by department and job titles.
- Compare the total employees between the headquarters (HQ) and the branches (New York is the HQ)
- Show the distribution of employees by city and state.

#### Demographics 

The Demographics section should offer insights into the composition of the workforce, including:

- Present the gender ratio in the company.
- Show the total number of employees within each age group.
- Show the total number of employees within each education level.
- Present the correlation between employee educational backgrounds and their performance ratings.

#### Income

The income analysis section should focus on salary-related metrics, including:

- Compare salaries across different education levels for both genders to identify any discrepancies or patterns.
- Present how the age correlates with the wages for employees in each department.

### Employee Records View
- Provide a comprehensive list of all employees with necessary information such as name, department, position, gender, age, education, and salary.
- Users should be able to filter the list based on any of the available columns.

##  Repository Structure
```
hr-analytics-tableau-project/
│
├── datasets/                           # Raw and cleaned HR datasets (CSV/Excel)
│
├── docs/                               # Project documentation and visuals
│   ├── hr_dashboard.png                # Screenshot of the final Tableau dashboard
│   ├── data_flow.drawio                # Data flow diagram for cleaning and preparation
│   ├── data_dictionary.md              # Explanation of dataset fields
│
├── tableau/                            # Tableau workbook (.twbx or .twb)
│
├── scripts/                            # SQL/Excel cleaning scripts if applicable
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information
└── .gitignore                          # Files and directories to be ignored
```
---

## Deliverables

- **Tableau Dashboard**: Visuals covering attrition analysis, employee demographics, and compensation trends.
- **Insights Report**: Key takeaways about workforce structure and retention drivers.
- **Data Flow Diagram**: Shows the pipeline from raw HR data to Tableau dashboard.

---

##  License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

##  About Me

Hi there! I'm **Simon Yang**. I’m a College Student on a mission to practice my skills and learn more about working with data.

Let's stay in touch! Feel free to connect with me on the following platforms:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/simon-yang-a5211535a/)
[![Handshake](https://img.shields.io/badge/Handshake-3DDC84?style=for-the-badge&logo=handshake&logoColor=white)](https://app.joinhandshake.com/profiles/ztjfa4)
