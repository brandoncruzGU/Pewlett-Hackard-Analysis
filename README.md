# Pewlett-Hackard-Analysis

## Overview of Analysis
The purpose of this analysis is to prepare Bobby and his team for the wave of employees who are retiring from Pewlett Hackard. Using a series of SQL commands, we helped Bobby apply filters to create several databases that are easier to interpret.

The first database we created captures the number of employees that are retiring per title. The current database includes employees who are not not eligible for retirement and also those who are no longer with the company. We will use several SQL queries to create a count of the number of employees who will retire this year.

The second database is comprised of retirees who are eligible for the mentorship program. This list will help Bobby and his team determine if they have enough people to train the remaining employees.

## Results
### The number of retiring employees by title
- We used a series of SQL queries to narrow down the list of people who are qualified to retire and used the "DISTINCT ON" command to ensure that employees are counted twice since they may have changed positions over time. 
- A majority of staff who are retiring either hold the title of senior level engineer (25,916) or a senior staff member (24,926). 
- The company will also lose a fair number of engineers (9,285) and staff members (7,636) during the next wave of retirements. 
- There are fewer technique leaders (3,603) and assistant engineers (1,090) who will retire this year. Lastly, there are only two managers who will retire this year.

### The employees eligible for the mentorship program
- Using the "DISTINCT ON" and "WHERE" commands, we were able to identify the number of people are about to retire.. 
- We applied the filter to only show employees who are born within the year 1965 and also those who no longer work with the company.
- There are 1,549 employees total who are eligible for the mentorship program. 
- There are 325 senior engineers, 291 senior staff employees,  413 engineers, 57 assistant engineers, 404 staff members, and 59 technique leaders who are eligible. 

## Summary
Pewlett Hackard will have 72,458 employees retiring this week. This is a significant drop in the number of employees at the company. There are 1,549 employees who are eligible for the mentorship program. We can infer that the number of eligible mentors will not be sufficient to train the number of employees who will replace the employees who are retiring.
