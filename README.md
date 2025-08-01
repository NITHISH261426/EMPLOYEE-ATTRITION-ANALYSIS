# EMPLOYEE-ATTRITION-ANALYSIS
This project involves the analysis and visualization of employee data to identify key factors influencing attrition within an organization. The dataset includes 1,480 employees and contains detailed information related to demographics, job satisfaction, compensation, work-life balance, performance, and more.
## 🎯 Project Objective

The objective of this HR Analytics project is to explore and visualize employee data to uncover key factors contributing to attrition within the organization. By analyzing trends across demographics, compensation, job satisfaction, and work-life balance, the goal is to provide actionable insights to HR and management teams to reduce turnover, improve employee retention, and enhance workplace satisfaction.

## 🛠️ Tools Used
*   **Power BI:** For data modeling, DAX calculations, and interactive visualizations.
*   **Power Query:** For data cleaning, transformation, and preparation.
*   
## 🗂️ Dataset Summary

The analysis is based on a comprehensive, simulated dataset representing internal HR records.

This HR Analytics dataset contains 1,480 employee records with 38 features related to demographics, job roles, satisfaction levels, compensation, and attrition.
It is used to analyze employee attrition patterns and identify key factors influencing turnover.
The data includes both categorical and numerical variables and is ideal for building dashboards and predictive models.

- <a href="https://github.com/NITHISH261426/EMPLOYEE-ATTRITION-ANALYSIS/blob/main/HR_Analytics.csv">Dataset</a>

## 📖 Data Dictionary

Below is a detailed description of each of the 38 columns in the dataset.



| Column Name                | Description                                                    |
| -------------------------- | -------------------------------------------------------------- |
| `EmpID`                    | Unique employee identifier                                     |
| `Age`                      | Age of the employee (in years)                                 |
| `AgeGroup`                 | Categorized age group (e.g., 18–25, 26–35)                     |
| `Attrition`                | Whether the employee has left the company (`Yes` / `No`)       |
| `BusinessTravel`           | Frequency of business travel                                   |
| `DailyRate`                | Daily rate of pay                                              |
| `Department`               | Department the employee belongs to                             |
| `DistanceFromHome`         | Distance between home and office (in km or miles)              |
| `Education`                | Education level (1: Below College, 2: College, ..., 5: Doctor) |
| `EducationField`           | Field of education (e.g., Life Sciences, Medical)              |
| `EmployeeCount`            | Always 1 (not meaningful, can be ignored)                      |
| `EmployeeNumber`           | Internal employee number (can be considered an alternate ID)   |
| `EnvironmentSatisfaction`  | Satisfaction with workplace environment (1: Low, 4: Very High) |
| `Gender`                   | Gender of the employee                                         |
| `HourlyRate`               | Hourly wage                                                    |
| `JobInvolvement`           | Level of involvement in job (1: Low, 4: Very High)             |
| `JobLevel`                 | Job seniority level (1 to 5)                                   |
| `JobRole`                  | Designation or job title                                       |
| `JobSatisfaction`          | Job satisfaction rating (1: Low, 4: Very High)                 |
| `MaritalStatus`            | Marital status (Single, Married, Divorced)                     |
| `MonthlyIncome`            | Total monthly income                                           |
| `SalarySlab`               | Salary range category                                          |
| `MonthlyRate`              | Monthly base salary                                            |
| `NumCompaniesWorked`       | Total number of companies worked for                           |
| `Over18`                   | All values are 'Y' (Not useful)                                |
| `OverTime`                 | Whether employee works overtime (`Yes` / `No`)                 |
| `PercentSalaryHike`        | Percentage increase in salary last year                        |
| `PerformanceRating`        | Performance rating (1: Low, 4: Excellent)                      |
| `RelationshipSatisfaction` | Satisfaction with relationships at work (1: Low, 4: Very High) |
| `StandardHours`            | Fixed standard working hours (always 80)                       |
| `StockOptionLevel`         | Stock option level granted (0 to 3)                            |
| `TotalWorkingYears`        | Total years of professional experience                         |
| `TrainingTimesLastYear`    | Number of training sessions attended last year                 |
| `WorkLifeBalance`          | Work-life balance rating (1: Bad, 4: Best)                     |
| `YearsAtCompany`           | Total years spent at the current company                       |
| `YearsInCurrentRole`       | Years spent in the current job role                            |
| `YearsSinceLastPromotion`  | Years since last promotion                                     |
| `YearsWithCurrManager`     | Years reporting to the current manager                         |

## 📊 Power BI Report

To present findings in an accessible and interactive format, a dashboard was created using Microsoft Power BI. This dashboard allows stakeholders to dynamically filter the data and explore sales trends on their own.

- <a href="https://github.com/NITHISH261426/EMPLOYEE-ATTRITION-ANALYSIS/blob/main/HR_Analytics_PowerBI.pbix">PowerBIReport</a>

## 💡 Key Findings & Insights

1.  **Overtime is a Critical Driver of Attrition:**
    *   Employees who work overtime have a significantly higher attrition rate (approx. **31%**) compared to those who do not (approx. **10%**). This suggests that burnout and poor work-life balance are major factors in an employee's decision to leave.

2.  **Vulnerability in Early-Career & Low-Income Roles:**
    *   Attrition is most severe among employees at **Job Level 1** and those in the **lowest salary slabs**.
    *   Roles like **Sales Representative**, **Laboratory Technician**, and **Human Resources** show the highest turnover rates, indicating potential issues with career pathing, compensation, or job satisfaction in these specific areas.

3.  **Demographic Trends in Turnover:**
    *   Younger employees in the **18-25 age group** are the most likely to leave the company.
    *   **Single** employees have a notably higher attrition rate compared to their married or divorced colleagues, suggesting that life stage and personal commitments play a role in retention.

4.  **The Impact of Employee Engagement and Satisfaction:**
    *   There is a strong negative correlation between attrition and satisfaction scores. Employees with low **Job Satisfaction** and **Environment Satisfaction** are far more likely to resign.

5.  **Business Travel Frequency Matters:**
    *   Employees who **Travel Frequently** for business exhibit a higher attrition rate than those who travel rarely or not at all, pointing to the strain that frequent travel can place on employees.
