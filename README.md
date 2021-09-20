# Overview
Pewlett Hackard is looking into the future and would like to prepare for the upcoming retirement of employees that will leave the company. This analysis will provide the company an overview of the upcoming amount of employees retiring, their positions, and what qualifies for training is needed to fill the vacancy of these employees that are retiring. 

# Analysis

1. In the retirement_title table, we obtained the total amount of employees by title that will retire, this was the result of joining the employees and titles table and filtering by the employees who were born between 1952 and 1955, the results showed indicated that 133.777 employees enter into the retairement age. 

2. On retirement_title table we noticed that employees id were duplicated because several employees holded different positions over the years, for that reason, we created the table unique_titles by filtering the retirement_title table using  distinct on statement.After this filter was implemented the result display 90.399 employees fit into the retirement criteria. 

3. On the retiring_table we organized the unique_title table by rearranged it by title and desendent order. 

4. Finally on the mentorship_eligibility table, we have created a table that hold the employees who are eligible to participate in a mentorship program. The condition to be eligible for this program is that need to be current employees whose birth date are between January 1, 1965 and December 31, 1965.The results display that 1550 employees are eligiable for mentorship. 

# Summary
This analysis provided us with an overview of the human resources panorama for the next years. To avoid a silver tsunami the company will have to file the role of 90.399 employees.Also, on regards to training and mentorship there is enough quialify/retirement employees to filled the demand of the current 1550 empployees that are eligible for mentorship.  
