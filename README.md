# HR Analytics Dashboard

## Project Overview

### Project Title
**HR Analytics Dashboard**

### Objective
This dashboard helps the HR department track the reasons for employee attrition and employee performance.

### Scope
- The dataset is sourced from Kaggle.
- Contains **1,470 rows** and **30 fields**.
- Each row represents an individual employee’s information, including job role, salary, work experience, and satisfaction level.

### Key Features of Dataset
- **Age**: Employee's age.
- **Attrition**: Indicates whether an employee has left the company (`Yes`/`No`).
- **Business Travel**: Frequency of business travel.
- **Department**: Employee's department (e.g., Sales, R&D).
- **DistanceFromHome**: Distance between home and workplace.
- **Education**: Education level (1 = Below College, 5 = Doctorate).
- **EmployeeNumber**: Unique identifier.
- **JobSatisfaction**: Satisfaction level (1 to 4).
- **MaritalStatus**: Marital status.
- **MonthlyIncome**: Employee's monthly salary.
- **OverTime**: Whether the employee works overtime (`Yes`/`No`).
- **PerformanceRating**: Performance score (1 to 4).
- **WorkLifeBalance**: Balance satisfaction (1 to 4).

## Project Timeline
| Phase               | Description                          | Estimated Duration |
|---------------------|----------------------------------|------------------|
| Data Collection    | Gathering relevant datasets       | 1 day           |
| Data Cleaning      | Handling missing values, duplicates | 0.5 day         |
| Data Modeling      | Defining relationships, measures  | 0.5 day         |
| Visualization      | Designing dashboard elements      | 3 days          |
| Final Review      | Testing and refining dashboard    | 1 day           |

## Data Collection & Preparation

### Data Sources
- The dataset is provided as a **CSV file**.

### Data Cleaning & Transformation
- **Removed duplicates** to ensure consistency.
- **Dropped irrelevant columns**, including `BusinessTravel`, `EducationLevel`, `DistanceFromHome`, `DailyRate`, `HourlyRate`, `Over18`, `StockOptionLevel`, and `StandardHours`.

## Dashboard Development

### Key Visualizations
- **Total number of employees**
- **Total attrition count & rate**
- **Active employees count**
- **Average employee age**
- **Attrition analysis by gender, department, and age range**
- **Impact of overtime & salary on attrition**
- **Performance rating distribution**
- **Relationship between job satisfaction and attrition**
- **Impact of training on performance**

### Measures & Calculations
- **Attrition Count** = Total employees who left (`Attrition = Yes`).
- **Attrition Rate** = `(Attrition Count / Total Employees)`.
- **Active Employees** = `(Total Employees - Attrition Count)`.
- **Overtime Rate** = `(Overtime Count / Total Employees)`.
- **Performance Categories**:
  - `3` → "Average Performer"
  - `4` → "Excellent Performer"

### Filters & Slicers
- **Department Filter**: Filter employees by department.
- **Job Role Filter**: Filter by specific job roles.

## Insights & Findings
- **Higher attrition among males**.
- **Salary influences attrition**: Competitive salary benchmarking needed.
- **Overtime impact**: Employees who don’t work overtime tend to leave more.
- **Age group 27-36 has the highest attrition**: Career growth a major factor.
- **R&D and Sales departments have high attrition rates**.
- **Majority of employees are rated as 'Average' performers**.
- **Attrition is higher among average performers**.
- **Targeted training in R&D and Sales could improve retention**.

## Challenges & Limitations
- **Navigating Tableau's interface and features was challenging.**

## Future Enhancements
- Optimize **data extracts** and use **Level of Detail (LOD) expressions**.
- Implement **interactive dashboard actions** for smoother user experience.

## Conclusion
- **Identifies key attrition factors**: Helps HR pinpoint retention issues.
- **Monitors employee performance trends**.
- **Provides department and job role-based insights**.

## Appendix
- **Resources Used**:
  - Tableau forums
  - Kaggle datasets
  - YouTube tutorials

