# School_District_Analysis

## Overview of the project

This project aims to analyze school data on student funding and students’ standardized test scores to showcase trends in schools’ performance based on the type, size, and budget. The result of the analysis will assist the school board and superintendent in making decisions regarding the school budgets and priorities. 

## Results
Because of evidence of academic dishonesty in Thomas High School, especially in 9th grade we had to replace the reading and math scores with NAN and repeat the analysis and we found the results below:

•	In the school district data frame, the average math, reading, and passing percentages for math reading and overall were slightly different after we cleaned the data. The scores and percentage decreased after cleaning the data.
pic
•	In the school summary data frame, the overall passing percentage in Thomas High School decreased from 91% to 65%. This clearly affected the ranking compared to other schools.
Pic

•	Replacing the nine graders’ math and reading scores affect Thomas High schools’ performance since the number of students remains the same but the number of students who passed math and reading decreased which result in a decrease in % of students who passed math and reading and overall percent scores.

Pic

To fix this we recalculated these percentages by subtracting the number of 9th-grade students from the total Thomas High School students. 

Pic 

•	The math and reading scores by grades were mostly affected in Thomas High school for the 9th grade where it appears nan in the data frame.
•	For the size, type, and spending data per schools’ data frames, the changes in the scores of math and reading test for the 9th grades in Thomas High School did not affect the scores in these groups. 



## Summary

In summary, replacing the 9th grader scores in Thomas High School by NAN affected the average scores in the overall school district where we saw a slight decrease in the scores. Also, they affected the ranking of Thomas School compared to other schools. In general, the % passing math, % passing reading, and % overall passing would be affected after deleting the 9th graders’ scores in Thomas School but since we recalculated these values after eliminating the 9th grade students’ scores, the % did not change at all.
