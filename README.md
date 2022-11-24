# Pewlett-Hackard-Analysis
## Overview of the analysis
The purpose of the analysis is to analyze data for the Company Pewlett-Hackard for employees who are going to retire in the next few years. 

## Results
Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.
* Create a table named retirement_titles with employees name, titles, and dates. 
* Use distinct on function to remove the duplicated entries and saved to table "unique_titles". 
```
SELECT DISTINCT ON (e.emp_no) e.emp_no,
```
* Finally created a table named retiring_titles and count the number of different titles. 
* Run a new query to create a new table of employees who were qualified for mentorship program named "mentorship_eligibilty". 


## Summary
Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
1. How many roles will need to be filled as the "silver tsunami" begins to make an impact?

    There are total 72,458 roles. 

2. Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees? 

    We have created a list of people who are qualified for mentorship programs with job titles and departments. 
    We don't have enough people to have 1 on 1 mentorship, but if we have group classes, we should have enough mentors. 

