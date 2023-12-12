# Objective:
The objective of this project is to identify the key factors driving employee attrition and provide actionable insights for improving workforce retention in an organization. This dashboard provides insights of the attrition of an organization which helps the HR team for their further analysis.

Throughout this project, I've had the chance to:

-Dive deep into HR data to uncover valuable insights.   
-Develop interactive dashboards to visualize key HR metrics.  
-Provide data-driven recommendations for strategic decision-making.

# Steps Followed:
1. Data Gathering:
   
•	Import raw data .xlsx file into Power BI & transform to Power Query editor for cleaning and data processing.

2. Data cleaning:
   
•	Cleaning is done by removing an empty column, removing duplicates, errors, etc.
•	Replacing values in columns with proper values and naming.
•	Detecting data type of every column, using the auto-detect data type function in the Power query editor.

3. Data processing:
   
•	In the Power Query editor, create a new column called "AttritionCount" by using the conditional column feature in the add column which is created based on certain conditions like (IF attrition = 'Yes' then 1, Else 0).
•	This new column is further used for creating different KPIs and charts. Then creating the Attrition Rate by applying DAX queries, adding new measure (Attrition Rate = SUM([AttritionCount]))/SUM([Employeecount])) in %.

4. Data analysis:
   
•	Analysis involves creating a range of visual representations, including bar charts, key performance indicators (KPIs), table charts, pie charts, and other relevant visualizations.
•	These tools are utilized to gain insights and present data comprehensively and easily understandable.

# Key Questions of the Dashboard :

-What is the Total Employee Count?          
-What is the employee's Average Age and average Salary?        
-What is the Attrition Count of men and women?       
-What are the employees Working years at the Company?        
-Which Department has the maximum number of employees?      
-What is the Gender distribution?          
-Which Education Field has the maximum number of employees?          
-Which Business Travel has the maximum employees?

# Learned about:
1.	Calculated Field: To Calculate Attrition Rate & Active Employees
2.	URL button: To take the employees feedback created feedback button which will navigate to Google Form.
3.	Scatter Chart: To show Attrition rate vs Monthly Income
4.	Donut chart and Pie Chart
5.	Bar Chart and Cluster chart 📊
6.	KPI(Key Performing Indicators) and Slicer.
7.	Filters: Used to filter data according to different education fields.
   
# Key Insights Summary:           
1.	Total Employees: The organization has grown significantly, currently employing 50000 individuals, indicating substantial growth and scale.
2.	Attrition Analysis: A total of 25105 employees left the organization. Among them, 17000 were male, and 8105 were female, indicating a higher attrition rate among males.
3.	Departmental Attrition: The Research and Development Department experienced the highest attrition rate at 51.13%, suggesting potential areas for improvement in employee retention strategies in this department.
4.	Monthly Income Impact: Employees having salary more than 40000 are leaving the organization more often, whereas employees whose salary is 10000 or less than that are staying in the organization for a longer time. 
5.	Job Role Affected: The sales role had the highest attrition rate, indicating a need for focused retention efforts in this department to reduce turnover.
6.	Attrition Rate by Gender for Different Age Group: The attrition count among the age group of 25-34 years 15000 which is maximum among the other age groups.



