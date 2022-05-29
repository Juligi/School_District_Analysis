Objective: to learn Python & achieve Conda and Jupyter knowhow
# A School District Analysis

## Overview & Purpose the school district analysis
For this mock project, I, the data analyst I'm paired up with Maria, the chief data scientist for a City School District.  We are tasked with preparing all standardized test data for analysis, reporting, and presentation to provide insights about performance trends and patterns to the leadership within the school district, to allow for better decision-making regarding the school budgets and priorities.  In this module, the task is to help Maria analyze data on student funding and students' standardized test scores.

This analysis of school data required learning how to use **_Anaconda_**, a free, open-source distribution software for over 1,500 packages suitable for Windows and macOS. and its subpackage: **_Jupyter Notebook_**.  With Jupyter Notebook, data analysts can "import data from a variety of formats, clean data, merge similar datasets, filter data based on conditionals, slice data on specific ranges, sort data based on values, and group data into similar categories. It can also be used to visualize data, write SQL queries, perform statistical analysis, and build and train machine learning models" according to this module instruction.

A School District Analysis was completed & submitted, however, post submission, the school board notified the data team that the [students_complete.csv file](https://github.com/Juligi/School_District_Analysis/blob/main/resources/schools_complete.csv) showed evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth-graders, which there appeared to have been altered. And while the school board did not know the full extent of the academic dishonesty, they want to uphold state-testing standards.  As result, all math and reading scores for Thomas High School must be replaced with NaNs while keeping the rest of the data intact, and the school district analysis must be repeated to compare whether the changes affected the overall analysis.  This ReadMe analyzes the latter.

## Results: Affect of Nullifying 9th Graders Scores on School and District Summaries, Scores by Grade, Math and Reading Scores, Scores by School Spending, School Size, and Type

### District summary
The District Summary was essentially not affected, and any effect statiscally is deemed negligible.
*  Prior average math scores sat at 79.0%, and post math scores for Thomas High School were replaced with "**NaNs**" the new score was reduced to 78.9%, displaying a minimal impact or delta.
*  No effect seen to average reading scores.  These remained unchanged at 81.9%.
  *  And, while no impact was seen to the average reading scores, the percent of students passing reading had a .1 decimal impact.  Prior scores before "**NaNs**" were introduced sat at 85.8% and with replacement scaled down to 85.7%, an insignificant downward slide for percent passing reading. 

How is the school summary affected?
### Replacing the ninth graders’ math and reading scores with Thomas High School’s & Affect performance relative to the other schools

Replacing

![image](https://user-images.githubusercontent.com/50222179/170856464-76b60e2a-8bb2-4b87-9e0d-641262168002.png)
vs
![image](https://user-images.githubusercontent.com/50222179/170856485-45e9b06d-248f-4f81-94e0-b6464ba72a37.png)


How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type

## Conclusion & Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
