# surfs_up

## Purpose of the Analysis
> The purpose of this project was to perform further queries on a temperature database on June and December temperatures on Oahu. The analysis of the results will help to determine the historical temperatures from low to high and then average. This will help our customer in their decision making process on whether or not to open a surf and ice cream store.

## Results:

Following are the most pertinent findings from the statistical analysis of the queries that were conducted (see figures for details):
- The high temperature between June and Decemeber does not vary significantly (83 in Dec and 85 in June).
- June is slightly higher on average than December (75 vs. 71 respectively).
- December low temperatures are a bit cooler than June (56 vs. 64 respectively).
### Statistical Summary
  ![June Temps Data](/Resources/June_temps.PNG)![December Temps Data](/Resources/Dec_temps.PNG)


## Summary:

1. How many roles will need to be filled as the "silver tsunami" begins to make an impact?
    > The unique_titles query revealed that there will be **90,398** employees retiring in the near future that the company may need to fill. 

2. Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
    > Although the mentorship eligibility query shows that there is a large number of employees elgible to be mentors (1549), that is only a small percentage of the retiring workforce: **1.7%**. That means that on a pure numbers perspective, each mentor would have to mentor about 59 employees if they want to fill all positions that will be vacated.

3. One query that may help PH increase the number of mentors is to expand the elgibility to current empoloyees that were born between 1/1/1964 and 12/31/1966. By expanding the eligibility to a three year time period, the number of possible mentors would increase to **19905**, an over 12 fold increase. *The results of this query can be seen in the mentorship_eligibility_exp file in the data folder.* 

4. Another query that could be helpful to PH in focusing on just the senior level employees that would be retiring to focus the mentoring efforts on those roles. We could conduct a query with the code below. This would reduce the number of total retirees to 57668 senior level positions. This may be a more manageable number for the mentors. If we use this number and combined it with the previous suggestion, each mentor would only have about 3 mentees. *See the retiring_senior.csv file in the data folder to see the results of this query.* 
