# Pewlett-Hackard-Analysis
## Overview
Our analysis of the employess at Pewlett-Hackard was done to assess the near future need for hiring new employees as the wave of baby boomers enter retirement. We determined the need for hiring and where it's most needed and at what levels. 

## Results 
After analyzing our data we determined the following:
- There are people retiring from a wide range of titles at the company.
- The highest area of concern for retiring employees in the near future is in the 'Senior Engineer' and 'Senior Staff' positions. Both of these positions have 24,000 to 26,000 employees ready to retire soon.

![Retiring Employee Count by Title](https://github.com/Trevor-Jackson94/Pewlett-Hackard-Analysis/blob/main/Images/Retiring%20Employee%20Count%20by%20Title.PNG)

- Based on the row count from our table with eligible mentors, there are still well over 1,000 employees (1549 employees to be exact) capable of mentoring. 
- The number of mentors compared to the amount of positions to fill is drastically less.

![Potential Unique Eligible Mentors](https://github.com/Trevor-Jackson94/Pewlett-Hackard-Analysis/blob/main/Images/Potential%20Eligible%20Mentors.PNG)

## Summary
Based on our analysis, there are 25,916 roles for Senior Engineers, 24,926 roles of Senior Staff, 9,285 engineer roles, 7,636 staff roles, 3,603 Technique Leader roles, 1,090 Assistant Engineer roles, and 2 Manager roles that will need to be filled as a result of the 'Silver Tsunami' impact. 

After further analysis a total of 1,549 eligible mentors still remain at the company. This drastically lower than the roles that we need to fill. The ability to mentor new employees in the near future with the retirement wave incoming could likely be a difficult situation to handle. 

To further understand the lack of mentorship at the company we could further analyze the number of mentors available in each department by joining our mentorship_eligibility table with the dept_emp table on the emp_no column and then to the department table on the dept_no column from the dept_emp table. This would help use better understand what departments are in dire need for mentors. 

We could also adjust our mentorship_eligibilty table's WHERE clause to broaden the age of eligible mentors and see how much the gap to the retiring employees is closed.

