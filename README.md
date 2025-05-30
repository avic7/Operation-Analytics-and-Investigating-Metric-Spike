# Operation Analytics and Investigating Metric Spike

## Overview
This project performs **end-to-end operational analytics** for a company to identify key areas for improvement. By querying and analyzing operational metrics using SQL, the project helps the **operations team** and **investors** make data-driven decisions quickly and accurately.

The main objective is to extract insights from a relational database, investigate anomalies like **metric spikes**, and guide operational strategy.


## Case Studies

### Case Study 1: Job Data Analysis
Dataset: `job_data` table with columns:
- `job_id`: Unique identifier of jobs
- `actor_id`: Unique identifier of actors
- `event`: Type of event (decision/skip/transfer)
- `language`: Language of the content
- `time_spent`: Time spent reviewing the job (seconds)
- `org`: Organization of the actor
- `ds`: Date in `yyyy/mm/dd` format

#### Tasks:
1. **Jobs Reviewed Over Time**
   - Objective: Calculate the number of jobs reviewed per hour for each day in November 2020.
   - Task: Write SQL query to extract jobs reviewed per hour.

2. **Throughput Analysis**
   - Objective: Calculate the 7-day rolling average of throughput (number of events per second).
   - Task: SQL query for rolling average throughput + recommendation on daily vs rolling average usage.

3. **Language Share Analysis**
   - Objective: Calculate the percentage share of each language over the last 30 days.
   - Task: SQL query to determine language distribution.

4. **Duplicate Rows Detection**
   - Objective: Identify and display duplicate rows.
   - Task: SQL query to find duplicate records in `job_data`.


### Case Study 2: Investigating Metric Spike
Datasets:
- `users`: Descriptive information for each user account.
- `events`: Records of user actions (e.g., login, messaging, search).
- `email_events`: Records related to email interactions.

#### Tasks:
1. **Weekly User Engagement**
   - Objective: Measure user activeness on a weekly basis.
   - Task: SQL query for weekly user engagement.

2. **User Growth Analysis**
   - Objective: Analyze user growth over time.
   - Task: SQL query for calculating growth trends.

3. **Weekly Retention Analysis**
   - Objective: Measure weekly retention based on sign-up cohorts.
   - Task: SQL query for cohort-based retention analysis.

4. **Weekly Engagement Per Device**
   - Objective: Track user engagement per device weekly.
   - Task: SQL query for engagement split by device type.

5. **Email Engagement Analysis**
   - Objective: Analyze user engagement with email services.
   - Task: SQL query to calculate email engagement metrics.



## Approach
- Load operational datasets into an SQL database.
- Write efficient SQL queries to uncover operational insights.
- Investigate anomalies (e.g., metric spikes) and recommend actions.
- Focus on enabling the operations team and stakeholders with actionable insights.



## Tech Stack
- **MySQL Workbench 8.0 CE** (Primary Tool)
- SQL (Structured Query Language)


## Requirements
To reproduce the analysis:

- SQL database management system (e.g., **MySQL**, **PostgreSQL**, **SQLite**)
- Access to the provided datasets
- Basic to intermediate knowledge of SQL syntax and aggregate functions


## How to Run

1. Load the datasets (`job_data`, `users`, `events`, `email_events`) into your DBMS.
2. Run the provided SQL queries sequentially in **MySQL Workbench** or your preferred SQL editor.
3. Analyze query results for insights.


## ontributing
Contributions are welcome! Feel free to:
- Open issues if you find bugs.
- Suggest new analytical tasks.
- Submit pull requests to expand the project.
