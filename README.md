This GitHub repository hosts a Power BI dashboard designed to analyze employee attrition trends, providing HR departments with actionable insights to reduce turnover. 
The project includes ETL (Extract, Transform, Load) processes to clean and structure raw employee data, removing redundant columns like EmployeeID and Over18 while focusing on key metrics such as department, job role, satisfaction scores, and 
compensation. The final dataset is visualized through interactive dashboards, highlighting critical trends—for example, Sales departments show a 33.33% attrition rate, and frequent business travelers are twice as likely to leave. Key DAX formulas, such as Attrition Rate (DIVIDE([Employees_Left], COUNTROWS(Employee_Attrition), 0)) and Avg Tenure (AVERAGE(Employee_Attrition[TotalWorkingYears])), power dynamic charts like gauge visuals and bar graphs. The repository is organized into folders for raw data, ETL scripts (Python), and the Power BI file, with plans to expand into predictive analytics.\
To use, run the ETL script, refresh the Power BI dashboard, and explore filters like education field or department to uncover attrition drivers.


Output overview:
![Outut_2](https://github.com/user-attachments/assets/ad95fc66-0bee-40ca-a561-86279bd306a3)
![Outut_1](https://github.com/user-attachments/assets/08b34b90-a092-4232-9539-fe9059a6a0ba)
