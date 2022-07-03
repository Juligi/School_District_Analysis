Objective: to learn Python & achieve Conda and Jupyter notebook knowhow
# A School District Analysis

## Overview & Purpose the school district analysis
For this mock project, I, the data analyst I'm paired up with Maria, the chief data scientist for a City School District.  We are tasked with preparing all standardized test data for analysis, reporting, and presentation to provide insights about performance trends and patterns to the leadership within the school district, to allow for better decision-making regarding the school budgets and priorities.  In this module, the task is to help Maria analyze data on student funding and students' standardized test scores.

This analysis of school data required learning how to use **_Anaconda_**, a free, open-source distribution software for over 1,500 packages suitable for Windows and macOS. and its subpackage: **_Jupyter Notebook_**.  With Jupyter Notebook, data analysts can "import data from a variety of formats, clean data, merge similar datasets, filter data based on conditionals, slice data on specific ranges, sort data based on values, and group data into similar categories. It can also be used to visualize data, write SQL queries, perform statistical analysis, and build and train machine learning models" according to this module instruction.

A School District Analysis was completed & submitted, however, post submission, the school board notified the data team that the [students_complete.csv file](https://github.com/Juligi/School_District_Analysis/blob/main/resources/schools_complete.csv) showed evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth-graders, which there appeared to have been altered. And while the school board did not know the full extent of the academic dishonesty, they want to uphold state-testing standards.  As result, all math and reading scores for Thomas High School must be replaced with NaNs while keeping the rest of the data intact, and the school district analysis must be repeated to compare whether the changes affected the overall analysis.  This ReadMe analyzes the latter.

## Results:

### Affect on School District Summary
The District Summary was essentially not affected, and any effect statistically is deemed negligible.
*  Prior average math scores sat at 79.0%, and post math scores for Thomas High School were replaced with "**NaNs**" the new score was reduced to 78.9%, displaying a minimal impact or delta.
*  No effect seen to average reading scores.  These remained unchanged at 81.9%.
  * And, while no impact was seen on the average reading scores, the percent of students passing reading had a .1 decimal impact.  Prior scores before "**NaNs**" were introduced sat at 85.8% and with replacement scaled down to 85.7%, an insignificant downward slide for percent passing reading grade.
  
The pictorials below are exemplary of the above summary of the findings. The image on the right is prior to the nullification of the grades discussed above, and the left is post nullification.  

![image](https://github.com/Juligi/School_District_Analysis/blob/main/resources/image.png)

### Affect on School Summary & Outcomes of Replacing the Ninth-grade Scores

Replacing the ninth graders’ math and reading scores with Thomas High School’s did not affect performance relative to the er schools, nor did it impact general math and reading scores by grade, scores by school spending, scores by school size, or scores by school type. For reference, review, the original data frame on the right versus left data frame taking into account the nullification of grades.
![image](https://github.com/Juligi/School_District_Analysis/blob/main/resources/School%20Summary_Original%20vs%20Challenge.png)


## Conclusion & Summary: 
No statistically significant delta occurred to the overall school district analysis after reading and math scores for the ninth grade at Thomas High School were replaced with NaN, nor, did it impact general school summary or scores by any category reviewed.  The School Board made a justified decision to uphold state-testing standards.  While, all math and reading scores for Thomas High School were replaced with NaNs while keeping the rest of the data intact, this school district analysis confirmed these changes did not affect the overall original analysis.
