# School District Analysis
This analysis reevaluates standardized test data from a city school district after it is discovered that the score averages for ninth graders from Thomas High School are incorrect. It continues to consider these ninth graders in the analysis as students, but replaces their scores to provide new insights on school districts and their performance in standardized tests. The following analysis evaluates the effect of replacing the ninth graders' math and reading scores.

## Recreating and evaluating district and school summary dataframes:
* While average math and reading scores only decrease by small amounts (0.05% and 0.02%, respectively), the percentage of students passing each subject decreases by roughly 1% each. 
![MyImage](Average_Scores.png)![MyImage](Average_Scores_Challenge.png)

* For Thomas High School, 431 less students pass math, and 452 less students pass reading on the standardized tests by virtue of replacing the ninth graders' scores.
![MyImage](Passing_Reading.png)![MyImage](Passing_Reading_Challenge.png)
![MyImage](Passing_Math.png)![MyImage](Passing_Math_Challenge.png)

* Overall passing falls dramatically from 90.94% of Thomas High School students passing to 65.07%.
![MyImage](Per_overall_passing.png)![MyImage](Per_overall_passing_Challenge.png)

## Recalculating high and low performing schools:
* Replacing the ninth graders' math and reading scores removes Thomas High School from the list of top 5 high schools in the city district, however it does not cause the school to be considered among the lowest scoring schools.
![MyImage](Top5.png)
![MyImage](Bottom5.png)

## Recalculating impact on scores based on:
a) Grade – There are no changes in the data, except for replaced data for Thomas High School for 9th graders. Other than that column displaying 'NaN', there are no changes.

b) School Spending – By replacing the scores of the 9th graders, we can see a change in the relationship between spending range per student and scores. We can observe that the percentage of students that pass math and reading overall decreases for the $630-644 spending category, which is the spending category under which Thomas High School falls. This decrease is explained by the fact that altering the data has decreased the number of students that pass reading and math attending 9th grade at Thomas High School (as explained above).
![MyImage](SpendingvScores.png)![MyImage](SpendingvScores_Challenge.png)

c) School Size – There is a change in the percentage of students who are passing overall in medium-sized schools as a result of removing the 9th graders' scores. Again, this is explained by the fact that Thomas High School is categorized as a medium-sized school: altering the data of the 9th graders causes the overall passing percentage to drop, hence changing the relationship between school-size and scores.


d) School Type –
