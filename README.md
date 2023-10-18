# Operation-Analytics-and-Investigating-Metric-Spike

The project operation analytics and investigating metric spike is analysis done for the complete end to end operations of a company. With the help of this, the company then finds the areas on which it must improve upon. The main objective of this project is to help the operations team and provide them accurate answers from the database using sql and various other techniques .

Case Study 1: Job Data Analysis
We will be working with a table named job_data with the following columns:
a)job_id: Unique identifier of jobs
b)actor_id: Unique identifier of actor
c)event: The type of event (decision/skip/transfer).
d)language: The Language of the content
e)time_spent: Time spent to review the job in seconds.
f)org: The Organization of the actor
g)ds: The date in the format yyyy/mm/dd (stored as text).

Tasks:
1.Jobs Reviewed Over Time:
Objective: Calculate the number of jobs reviewed per hour for each day in November 2020.
Task: Write an SQL query to calculate the number of jobs reviewed per hour for each day in November 2020.
2.Throughput Analysis:
Objective: Calculate the 7-day rolling average of throughput (number of events per second).
Task: Write an SQL query to calculate the 7-day rolling average of throughput. Additionally, explain whether you prefer using the daily metric or the 7-day rolling average for throughput, and why.
3.Language Share Analysis:
Objective: Calculate the percentage share of each language in the last 30 days.
Task: Write an SQL query to calculate the percentage share of each language over the last 30 days.
4.Duplicate Rows Detection:
Objective: Identify duplicate rows in the data.
Task: Write an SQL query to display duplicate rows from the job_data table.

Case Study 2: Investigating Metric Spike
You will be working with three tables:
a)users: Contains one row per user, with descriptive information about that user’s account.
b)events: Contains one row per event, where an event is an action that a user has taken (e.g., login, messaging, search).
c)email_events: Contains events specific to the sending of emails.

Task
1.Weekly User Engagement:
Objective: Measure the activeness of users on a weekly basis.
Task: Write an SQL query to calculate the weekly user engagement.
2.User Growth Analysis:
Objective: Analyze the growth of users over time for a product.
Task: Write an SQL query to calculate the user growth for the product.
3.Weekly Retention Analysis:
Objective: Analyze the retention of users on a weekly basis after signing up for a product.
Task: Write an SQL query to calculate the weekly retention of users based on their sign-up cohort.
4.Weekly Engagement Per Device:
Objective: Measure the activeness of users on a weekly basis per device.
Task: Write an SQL query to calculate the weekly engagement per device.
5.Email Engagement Analysis:
Objective: Analyze how users are engaging with the email service.
Task: Write an SQL query to calculate the email engagement metrics.

Approach :
The main approach towards this project to help and assess the ops team and investors with the
insights they need is by first loading the database performing various sql queries to get the exact
insights the team needs quickly.
Tech used : The main software used during the project is MySql Workbench 8.0 CE

Requirements
1. To run the SQL queries and reproduce the insights in this project, you'll need:
2. An SQL database management system (DBMS) such as MySQL, PostgreSQL, or SQLite.
3. Access to the provided dataset.
4. A basic understanding of SQL query syntax and functions.

Contributing
Contributions to this project are welcome! If you find issues, have suggestions, or want to add new analytical tasks, feel free to submit pull requests.

This project intends to deliver significant insights that help drive data-driven decision-making and enhance many elements of the organisation by doing in-depth analyses and investigations on operational indicators using SQL.
