# Pewlett-Hackard-Analysis 🖥️

## 1. Overview 

This project aims to determine the number of retiring employees eligible to participate in a mentorship program. The following deliverables will be the outcome of the analysis.

* Deliverable 1: The Number of Retiring Employees by Title
* Deliverable 2: The Employees Eligible for the Mentorship Program
* Deliverable 3: A written report on the employee database analysis

## 2. Results

1) On extracting the Retiring Employees by Title, it was evident that the rows do not have unique employee numbers as there are employees who had held multiple titles. Moreover, the list has employees who left the company
2) To highlight the single instances, DISTINCT ON was used on emp_no and to get the current employees, only rows with '9999-01-01' under "to_date" was sorted
3) Our third query helped with listing the counts
![](https://github.com/AllenAx91/Pewlett-Hackard-Analysis/blob/main/Count_Title_For%20report.png)
4) Our last query was to create a mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965

## 3. Summary

* Once the "silver tsunami" takes effect, the total number of vacant roles would be **72458**. 
* The total number of qualified, retirement-ready employees in the departments to mentor the next generation is **1549**. Our last query was to create a mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965


