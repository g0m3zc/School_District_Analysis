# School_District_Analysis
Analysis for testing data using Pandas &amp; Jupiter Notebook


## Project Overview
Overview of the school district analysis:
This project consisted of providing an analysis of school district data through the following steps.
1.  Performing data clean up such as by correcting names and missing data.
2.  Completing an inital analysis of the data.
3.  Making updates to remove the math and reading scores for 9th graders in Thomas High School.  This required updating the data in question to NaNs so that it is not impacting the final results.
4.  Repeating the analysis of the school data.


## Resources
- schools_complete.csv
- students_complete.csv
- Pandas
- Numpy
- Jupiter Notebook

In this analysis we used loc method to retrieve the appropriate data for each step.  


## Summary:
These findings are comparing the original analysis against an updated version which removed data from the group in question.
The impacts to the Thomas school summary included
- % passing reading decreased from 97.3 to 66.9
- % passing math decreased from 93.3 to 88.9
- Overall % passing math & reading decreased from 91.0 to 65.1


The impacts to the school district analysis included:
- The % passing math was lower in the updated analysis.
- % passing reading was lower in the updated analysis.
- The overall % passing in math and reading was also lower.

Original
![original_district_summary](https://user-images.githubusercontent.com/106936638/179157533-ff9294f8-8bbc-4177-bed2-ecda64cbdbad.PNG)

Updated
![updated_district_summary](https://user-images.githubusercontent.com/106936638/179157540-975d83bb-cf4a-469d-8bb3-fe199fd2dbba.PNG)


## Recommendations:
A recommendation to take this step forward could include removing the student name column to protect student privacy after the initial review of the data is completed.
