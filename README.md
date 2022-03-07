# School_District_Analysis

## Overview of the project

This project aims to analyze school data on student funding and students’ standardized test scores to showcase trends in schools’ performance based on the type, size, and budget. The result of the analysis will assist the school board and superintendent in making decisions regarding the school budgets and priorities. 

## Results
Because of evidence of academic dishonesty in Thomas High School, especially in 9th grade we had to replace the reading and math scores with NAN and repeat the analysis and we found the results below:

•	In the school district data frame, the average math, reading, and passing percentages for math reading and overall were slightly different after we cleaned the data. The scores and percentage decreased after cleaning the data.
 ### Before cleaning the data
![before district_summary](https://user-images.githubusercontent.com/66279829/157001736-4cac849b-be0e-482e-a63c-0bfb4dd6a782.PNG)

### After cleaning the data
![after district_summary](https://user-images.githubusercontent.com/66279829/157001800-dfacee77-c66c-489d-8d4d-0c82d0357024.PNG)

•	In the school summary data frame, the overall passing percentage in Thomas High School decreased from 91% to 65%. This clearly affected the ranking compared to other schools.

![before per_school_summary](https://user-images.githubusercontent.com/66279829/157001834-64b2b9f3-58e0-43ff-b9ce-1ef2c5d09047.PNG)

•	Replacing the nine graders’ math and reading scores affect Thomas High schools’ performance since the number of students remains the same but the number of students who passed math and reading decreased which result in a decrease in % of students who passed math and reading and overall percent scores.

![after per_school_summary](https://user-images.githubusercontent.com/66279829/157001879-1be70ec9-5e1c-42b8-9f0d-185c7638a5d2.PNG)

To fix this we recalculated these percentages by subtracting the number of 9th-grade students from the total Thomas High School students. 

![after per_school_summary 2](https://user-images.githubusercontent.com/66279829/157001915-d1d11357-7874-4a5d-ae5b-ae987cfc85f2.PNG)

•	The math and reading scores by grades were mostly affected in Thomas High school for the 9th grade where it appears nan in the data frame.
•	For the size, type, and spending data per schools’ data frames, the changes in the scores of math and reading test for the 9th grades in Thomas High School did not affect the scores in these groups. 

## Summary

In summary, replacing the 9th grader scores in Thomas High School by NAN affected the average scores in the overall school district where we saw a slight decrease in the scores. Also, they affected the ranking of Thomas School compared to other schools. In general, the % passing math, % passing reading, and % overall passing would be affected after deleting the 9th graders’ scores in Thomas School but since we recalculated these values after eliminating the 9th grade students’ scores, the % did not change at all.
