This project focuses on creating dashboards in Power BI using data for survey takers. The dataset comprises 631 entries and includes various fields such as:
- Unique ID
- Email
- Date Taken (America/New_York)
- Time Taken (America/New_York)
- Browser
- Operating System (OS)
- City
- Country
- Referrer
- Time Spent
- Q1: Which title best fits your current role?
- Q2: Did you switch careers to Data?
- Q3: Current yearly salary (in USD)
- Q4: What industry do you work in?
- Q5: Favorite programming language
- Q6: How happy are you in your current position regarding the following aspects?
  - Salary
  - Work-life balance
  - Coworkers
  - Management
  - Upward mobility
  - Learning new things
- Q7: How difficult was it for you to break into Data?
- Q8: If you were to look for a new job today, what would be the most important factor for you?
- Q9: Gender (Male/Female)
- Q10: Current age
I created dashboards to visualize various key performance indicators (KPIs) for better analysis. This project focuses on creating dashboards in Power BI using grocery data from Blinkit. The dataset comprises 8,424 entries and includes various fields such as:

- Unique ID
- Email
- Date Taken (America/New_York)
- Time Taken (America/New_York)
- Browser
- Operating System (OS)
- City
- Country
- Referrer
- Time Spent
- Q1: Which title best fits your current role?
- Q2: Did you switch careers to Data?
- Q3: Current yearly salary (in USD)
- Q4: What industry do you work in?
- Q5: Favorite programming language
- Q6: How happy are you in your current position regarding the following aspects?
  - Salary
  - Work-life balance
  - Coworkers
  - Management
  - Upward mobility
  - Learning new things
- Q7: How difficult was it for you to break into Data?
- Q8: If you were to look for a new job today, what would be the most important factor for you?
- Q9: Gender (Male/Female)
- Q10: Current age

First, I cleaned the data in Power BI by deleting all unnecessary columns. I also split columns using delimiters and standardized the "Favorite Programming Language" and "Which Title Best Fits Your Current Role" columns. 

For the "Current Yearly Salary," I used the find and replace option to clean the data. Additionally, I added a new column to calculate the total average salary.

Next, I moved on to calculate various key performance indicators (KPIs):

1. Count of Distinct IDs  
   - Chart Type: Card

2. Average Age of Survey Takers  
   - Chart Type: Card

3. Average Salary by Job Title  
   - Chart Type: Stacked Bar Chart

4. Count of Countries of Survey Takers  
   - Chart Type: Tree Map

5. Favorite Programming Language  
   - Chart Type: Stacked Column Chart

6. Happiness with Work-Life Balance  
   - Chart Type: Gauge

7. Happiness with Salary  
   - Chart Type: Gauge

8. Average Salary by Gender  
   - Chart Type: Donut/Pie Chart
  
   - ![image](https://github.com/user-attachments/assets/5cab35d7-65fb-40d2-adbe-3b83e5e241c7)

