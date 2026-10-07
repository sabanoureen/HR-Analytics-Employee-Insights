# HR Analytics & Employee Insights

## Project Overview

This project analyzes employee data to uncover insights into workforce characteristics, employee performance, salary patterns, and employee attrition.

The project uses Python and Pandas to perform data cleaning, exploratory data analysis, feature engineering, grouping, aggregation, filtering, and business-oriented analysis.

The goal is to transform raw HR data into meaningful insights that can support better workforce and HR decision-making.
## Dataset

The dataset contains employee-level HR information used to analyze workforce characteristics, compensation, performance, satisfaction, and attrition.

### Dataset Size

- **Rows:** 1,500 employees
- **Columns:** 31
- **Format:** CSV

### Main Areas Covered

- Employee demographics
- Department and job information
- Salary and experience
- Performance and satisfaction
- Overtime and remote work
- Projects completed
- Training hours
- Leave days
- Promotions
- Employee attrition
## Tools & Technologies

- **Python**
- **Pandas** — data cleaning, transformation, filtering, grouping, aggregation, and analysis
- **NumPy** — conditional logic and numerical operations
- **Matplotlib** — data visualization
- **Seaborn** — statistical visualization
- **Jupyter Notebook** — analysis and documentation
## Data Analysis Process

The project follows a structured data-analysis workflow:

1. **Data Quality Audit**
   - Inspected dataset shape and structure
   - Checked data types
   - Identified missing values
   - Checked for duplicate records

2. **Data Cleaning**
   - Standardized categorical values
   - Handled missing values
   - Converted columns to appropriate data types
   - Cleaned and prepared date-related fields

3. **Feature Engineering**
   - Created employee experience levels
   - Created salary groups
   - Created training and project groups
   - Created leave-day groups
   - Created binary indicators for analysis

4. **Exploratory Data Analysis**
   - Analyzed employee attrition
   - Compared salaries across departments
   - Examined employee performance
   - Studied training, projects, overtime, leave, and promotions

5. **Group-Based Analysis**
   - Department-level analysis
   - Gender-level analysis
   - Department + gender analysis
   - Department + experience-level analysis

6. **Business Insights**
   - Identified groups with higher attrition
   - Compared compensation and performance
   - Evaluated workforce patterns
   - Used multiple conditions to identify departments requiring attention
## Key Business Questions

The analysis investigates questions such as:

- Which department has the highest employee attrition rate?
- Does overtime relate to employee attrition?
- How does attrition vary by gender?
- How does remote work relate to attrition?
- Which experience level has the highest attrition?
- Does salary level relate to employee attrition?
- How does promotion status relate to attrition?
- Does employee performance relate to attrition?
- How does satisfaction relate to attrition?
- Which departments have the highest average salaries?
- Which departments have the highest average performance scores?
- Which departments have the highest average number of completed projects?
- How does salary vary by department and gender?
- How does salary vary across experience levels?
- Which department and gender combination has the highest attrition rate?
- Which departments show strong performance, salary, and project outcomes simultaneously?
- Which departments may require further HR attention based on multiple workforce indicators?
## Project Structure

```text
hr-analytics-employee-insights/
│
├── data/
│   └── employee_hr_analytics.csv
│
├── hr_analytics_employee_insights.ipynb
│
├── requirements.txt
│
├── .gitignore
│
└── README.md
## Key Findings

The analysis identified several patterns across employee demographics, compensation, performance, and attrition.

How to Run
pip install -r requirements.txt
jupyter notebook

Open hr_analytics_employee_insights.ipynb to explore the analysis.

Key Focus

Data Cleaning → Feature Engineering → Exploratory Analysis → Business Insights