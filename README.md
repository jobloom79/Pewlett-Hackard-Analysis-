# Pewlett-Hackard-Analysis
## The "Silver Tsunami" phenomenon
### Overview of Project:
---The purpose of this analysis is to assess the known phenomenon of mass retirement within the organization and combat its effect on the workforce and the business as a whole.
### Analysis and Challenges:
#### Deliverable 1: Determining retiring employees
---Using the data retrieved from the employees table extracted from the employee database created earlier in the project the information on retirement employees was filtered using several SQL commands like 'JOIN', 'WHERE' and 'ORDER BY' to list all the employees eligible for retirement and exported using the 'COPY TO' command to the following path [Retirement Titles](https://github.com/jobloom79/Pewlett-Hackard-Analysis/blob/main/Data/retirement_titles.csv)

---The 'DISTINCT ON' statement was then used to retrieve the most recent and unique title of the employees eligible for retirement and exported to the following path [Unique Titles](https://github.com/jobloom79/Pewlett-Hackard-Analysis/blob/main/Data/unique_titles.csv)

---The final step of the data retrieval was to query for the number of retiring titles filled by employees retiring using the 'COUNT' command and sorting by the count. The result was exported to the following path [Retiring Titles](https://github.com/jobloom79/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.csv)
#### Deliverable 2: Determining employees eligible for the mentorship program
---This deliverable was retrieved extracting from the employees table employees born between January 1, 1965 and December 31, 1965. In order to accomplish this 'DISTINCT ON' command was used to get the unique employee numbers and a filter applies using 'WHERE' and 'ORDER BY' to get the birth dates and to dates of the employees, while sorting them by employee number. The data was exported to the following path  [Mentorship](https://github.com/jobloom79/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibilty.csv)
### Results:
---The Analysis helped to provide a large list of employees retiring and help filter down the results to specific outputs as requested, resulting in better visibility into retirments by job title, while also scrubbing the data of any duplications and other unneeded information.

---In addition it was determined the list of employees that are eligible to mentor junior personnel approximately 10 years before the retirement age
### Summary: 
---In Summary the results validate the concern of not only the fact that there are many employees set to retire, but the sheer amount of employees at retirement age who will be leaving the company with valuable experience. The "Silver Tsunami" as it is called can potentially harm the operations of the company and in turn the quality of the line of products that flagship the business and its bottom line.

---In order to tackle this threat an assessment of the employees eligible for the mentorship program was taken and the result was 1,549 potential mentors across the departments which. This gives encouragement the company can better prepare itself for the mass exodus by transferring knowledge over the span of the next 10 years across all the departments and retain the knowledge within the company.

---Further Analysis on the "emp_info data" located [Employee Info](https://github.com/jobloom79/Pewlett-Hackard-Analysis/blob/main/Data/emp_info.csv) and "manager info data" located [Manager Info](https://github.com/jobloom79/Pewlett-Hackard-Analysis/blob/main/Data/manager_info.csv) reveals insight into possible causes for the deficiencies in employee growth and retention. There seems to be a lack of leadership in the organization and a lack of mentoring, which may be a result of not enough incentives. One solution already being addressed is mentorship of junior talent. The other solution is improvement on salary increases, performance based bonuses, and opportunities for promotion. Some other incentives that seem to be more in demand is work life balance and flexibility arrangements to work remotely part or full time. All of these can help to change the culture and battle the retention and knowledge transfer problems and the phenomenon of the "Silver Tsunami" will not even be a factor, but an expected progression that the company is well prepared for.
