# School_District_Analysis
Academic performance on a small sample (15) of district and charter schools

## Overview
On this project we'll be going through the reading and math scores of schools in the district with the purpose of evaluating their testing proficiency. Also, each school's type (charter or district), size (small - large) and budget (via per capita spending) will be used in our analysis to establish the relationship they hold with student performance.

## Results
Scores by School Spending (per capita spending)
- The lowest range or 'bin' ($ 0 - $ 584) had the highest overall passing percentage, showing that the money spent on a student doesn't have a positive realation with their academic performance as much as, let's say, the quality of the teachers and the teaching system, as well as the administration and organization strategies from the heads of each school

Scores by school Size
- Schools tend to have a lower passing rates as well as lower averages when the student count is above 2000. The impact shows claerly in the table above, with the % Overall Passing being 58% in large size schools, compared to the 91% obtained in its medium size counterparts. Ther isn't much difference among small to medium size schools, wich could mean that a classroom with fewer students in it, could receive more attention from the staff, and teachers could take care of the details that keep alumni from advancing in each subject, thus overcoming the challenges presented to them on a daily basis. 

Scores by school type
- The results show that Charter schools performed at a higher level on all categories (averages and overall pasing rate) but, focusing on the reading subject, the average for district shools was not that far from the charter schools average - less that 3 porcentual point -. So sure, the reading deparment needs to improve, but more attention should be put on the math department, with an average as low as 76% no wonder only 66% of alumi accomplished a passing score, this number should be at least the same as the % passing reading (80%).

I think, the overall insights of the analysis, accounts for the advantages that come with the freedom or "flexibility" in  the operation of a charter school. They take greater responsability by not adhering to all regulations applied to district school, and deliver great results. A particular system may not work for every student, and not all charter schools are the same. But, given the opportunity, a group of individuals (teachers, administration staff) could take on the challenge of improving the way teaching is presented, bring clarity to the learning process and conrtibute to developing the mind on each student that they can.  

## Summary

This weeks challenge angle was improve our skills in locating and altering data to seee how this changes would alter our school district analysis. Due to a dishonest academic decision, all the reading and math scores for Thomas High School (THS) ninth graders were replaced with NaNs, while keeping the rest of the data intact.

After performing another analysis with "clean data" we don't observe mayor variations in the results.

- Original district summary shown below:

<Img src="Images/Original%20district%20summary.png" width="650">

  
- District summary with clean data
<Img src="Images/Challenge%20district%20summary.png" width="650">
  
However, the spending summary shows some notable differences between the original and the challenge analysis

- Original spending summary 
<Img src="Images/Original%20spending%20summary.png" width="650">  
  
- Spending summary with clean data
<Img src="Images/Challenge%20spending%20summary.png" width="650">
  
If we look at the second table, all the values for the third bin ($630 - $ 644) were affected by the removal of ninth graders scores. The averages and passing percentages suffered a downturn, with the overall passing percentage being the highest of them all (almost ten porcentual points). This is due to the fact, that while we susbstract ninth graders scores (consisting in 461 rows with values) the budget stays the same, thus more money (spending per capita) will be invested in each alumnus, going from $638 to $888.53. This creates a situation where THS spending range goes over the pre-established limits (or bins) leaving all the failing and passing grades out of it. In this case, removing the scores affected negatively the overall performance of THS.



