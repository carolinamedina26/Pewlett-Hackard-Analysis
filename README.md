# Overview
Pewlett Hackard is looking into the future and would like to prepare for the upcoming retirement employees that will leave the company. This analysis will provide the company an overview of upcoming amount of employees retiring, position that are holding, and what employees quality for training to fill the vacancy of this employees that are retiring. 

# Analysis

1. In the retirement_title table, we obtained the total amount of employees by title that will retire, this was the result of  joining the employees and titles and filtering by the employees who were born between 1952 and 1955. 

2. On retirement_title table we noticed that employees id were duplicated because several employees folded different positions over the year, for that reason, we created the table unique_titles by filtering the retirement_title table using < distinct on> statement. 

3. On the retiring_table we organized the unique_title table by rearranged it by title and depending order. 

4. Finally on the mentorship_eligibility table, we have created a table that hold the employees who are eligible to participate in a mentorship program. The condition to be eligible for this program is that need to be current employees whose birth date are between January 1, 1965 and December 31, 1965.
