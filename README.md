##Employee Data Analysis Project README

Hey there! Thanks for checking out this project. This repository contains all the necessary files to set up and run a detailed analysis on employee data using SQLite.

The main goal of this project was to understand the employee landscape—things like experience level distribution, salary structure, how long people stay, and recent hiring trends.

### Project Contents

The analysis is based on a simple SQLite database and structured using the following files:

* **`DataExtraction.sql`**: This is the heart of the project. It includes all the SQL commands to:
    * Create the `Employee` table 
    *Insert **26 sample employee records**.
    * Add the `ExpLevel` column and categorize employees based on their `PrevExperience`
    * Execute all the analytical queries (distribution, salary, tenure, etc.).
* **`EmployeeAnalysisDB.db`**: This is the actual SQLite database file containing the structured employee data.
* *`Detailed Analysis Report.pdf`**: This is a summary report detailing the findings from the SQL analysis, written by me: Jabulani Romeo Ndlovu. It includes the queries used and a brief discussion of the results for distribution, salary, tenure, recent hires, and demographic analysis.

### 💻 How the Analysis Works

The analysis defines five key experience levels based on `PrevExperience` (in years):

| PrevExperience (Years) | Experience Level |
| :--------------------: | :--------------: |
| 1 - 2                  | Intern           |
| 3                      | Junior           |
| 4                      | Associate        |
| 5 - 7                  | Intermediate     |
| 8 - 10                 | Senior           |
| 10+                    | Manager          |

The core analysis covers:

1.  **Employee Distribution**: Counting employees by their experience level .
2.  **Salary Analysis**: Calculating the average, minimum, and maximum salaries per experience level 
3.  **Tenure**: Finding the average years of service for employees within each level.
4.  **Hiring Trends**: Identifying the number of employees hired after 2020-01-01 
5.  **Demographics**: Determining the most common birthday month for each level and analyzing P.O. ox address trends .

###Getting Started

To run this analysis yourself, you'll need an environment that supports SQLite/SQL Server:

1.  **Clone this repository, the extract the files youll need**
2.  **Open the `.db` file** with any SQLite client (like DB Browser for SQLite or a command-line interface).
3.  **Execute the queries** from the `DataExtraction.sql` file in your SQLite client to see the results of the analysis in real-time.

Happy analyzing!
