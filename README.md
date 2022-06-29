# Pewlett-Hackard-Analysis

## Overview of the analysis: 

The purpose of this analysis was to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program.  
For the first analysis, I began by creating a Retirement Titles table that holds all the titles of employees who were born between January 1, 1952 and December 31, 1955. I also used the DISTINCT ON statement to create a table that contains the most recent title of each employee. Then, used the COUNT function to create a table that has the number of retirement-age employees by most recent job title. Finally, I filtered to include only current employees in my analysis, to be sure to exclude those employees who have already left the company.
For the second analysis, I created a table for mentorship-eligibility that holds the current employees who were born between January 1, 1965 and December 31, 1965.

## Results: 

After performing the analysis, there are several take aways that can be concluded:

- Of the roughly 300,000 current employees, roughly 71,000 will be retiring soon.
- The majority of the staff who will be retiring soon are either senior level engineers or staff.
- Only two managers will be retiring.
- There are far fewer employees who will be eligable for the mentorship program than those who are retiring soon.

Below are the tables of the retiring titles and mentorship eligibility.

Retirng Titles

<img width="212" alt="Screen Shot 2022-06-28 at 9 00 26 PM" src="https://user-images.githubusercontent.com/105119531/176435882-72ae10a3-5f35-42ef-b225-da0f397c229e.png">

Membership Eligibilty

<img width="524" alt="Screen Shot 2022-06-29 at 8 27 13 AM" src="https://user-images.githubusercontent.com/105119531/176436235-fb13bc6a-cc7e-4de1-b165-e78bcc07c327.png">

## Summary: 

From the analysis, we are left with a few questions to answer, first, how many roles will need to be filleed as the "silver tsunami" begins to make an impact? To answer this question, it would be benificial to dive deeper into the each of the coming years individually to see how many employees will be leaving per year. There is a total of ~71,000 employes retiring in the next 4 years, so there will be about that many positions to fill, some of which can be filled internally through promotions but will still open up more entry level positions.  One thing that is very clear from the analysis is that there are nowhere near enough employees who are qualified for the mentorship program to be able to help fill the need that the "silver tsunami" will leave.  
Additional questions that still need to be answered are, how many employees will need to be hired each year and would it be possible to expand the criteria for the mentorship eligibilty to include more current employees to handle the incoming hiring need?

