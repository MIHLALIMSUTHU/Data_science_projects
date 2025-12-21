# Data_science_projects
All my data science projects using python libraries.



# Salary Data Analysis with Pandas--Mihlali's_first_pandas_project

## Project Overview
This project performs an exploratory data analysis (EDA) on a dataset containing salary information. The goal is to understand various aspects of employee compensation, job titles, and other related metrics.

## Dataset
The analysis uses the `Salaries.csv` dataset, which contains detailed information about employee salaries, including:
- `Id`: Employee ID
- `EmployeeName`: Name of the employee
- `JobTitle`: Job title of the employee
- `BasePay`: Base salary
- `OvertimePay`: Overtime compensation
- `OtherPay`: Other forms of compensation
- `Benefits`: Employee benefits
- `TotalPay`: Total pay (BasePay + OvertimePay + OtherPay)
- `TotalPayBenefits`: Total pay including benefits
- `Year`: Year of the salary record
- `Notes`: Additional notes (dropped during analysis)
- `Agency`: Agency (dropped during analysis)
- `Status`: Employment status (dropped during analysis)

## Analysis Steps
The following steps were performed as part of this analysis:
1.  **Data Loading**: The `Salaries.csv` dataset was loaded into a pandas DataFrame.
2.  **Initial Data Inspection**: Checked the head, tail, shape, and information (`.info()`) of the dataset.
3.  **Handling Missing Values**: Identified and handled missing values, including converting 'Not provided' strings to `NaN` and converting 'BasePay' to numeric type.
4.  **Data Cleaning**: Dropped irrelevant columns such as 'Id', 'Notes', 'Agency', and 'Status'.
5.  **Descriptive Statistics**: Generated overall statistics for the DataFrame using `describe()`.
6.  **Employee Name Analysis**: Found the top 5 most frequent employee names.
7.  **Job Title Analysis**: Counted unique job titles, found the number of job titles containing 'Captain', and extracted employee names for jobs containing 'Fire'.
8.  **BasePay Analysis**: Calculated minimum, maximum, and average BasePay.
9.  **Specific Employee Inquiry**: Found the job title and total pay with benefits for 'ALBERT PARDINI'.
10. **Highest Earner**: Identified the employee with the highest BasePay.
11. **Average BasePay by Year and JobTitle**: Calculated the average BasePay per year and per job title, including for a specific job title like 'ACCOUNTANT'.
12. **Most Common Jobs**: Identified the top 5 most common job titles.

## Tools and Libraries
-   **Python 3**
-   **pandas**: For data manipulation and analysis.
-   **NumPy**: Used for numerical operations and `NaN` representation.

## How to Run
1.  Ensure you have Python and the necessary libraries (pandas, numpy) installed.
2.  Download the `Salaries.csv` file.
3.  Open the Colab notebook (`Mihlali's_first_pandas_project.ipynb`).
4.  Run the cells sequentially to reproduce the analysis.
