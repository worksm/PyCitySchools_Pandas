# School_District_Analysis
Analyzing PyCity school district utilizing Pandas. 
## Overview of the school district analysis:
The school district analysis aims to provide the client wiht a high-level overview of PyCity School Districts' key metrics, presented in a table format. The anaylsis also includes an overview of key metrics for each school, presented in table format. The final product for the client, was refactored to remove Thomas High School's 9th grade scores, due to fear of academic dishonesty. The district analysis provides a multifocal data analysis and comprehensive view in an end-user friendly format. 

## Results:
* ### How is the district summary affected?
 * The removal of Thomas High School's 9th grade students from the dataset had minimal impact on the district summary. Total Students, Average Math Score, % Passing Math, and % Passing Reading all had minor decreases from their original scores. See images below for details. 

  * #### Original PyCity School District Summary

![PCS_District_Summary_1](https://github.com/worksm/School_District_Analysis/blob/828659908e4cedb3fdfb31555dc14a54df1dc4f8/School_District_Analysis/Resources/PCS_District_Summary_1.png)

  * #### Updated PyCity School District Summary

![PCS_District_Summary_2](https://github.com/worksm/School_District_Analysis/blob/7c8114ea6ee74a33ecd02a85e72afbc46a7c1067/School_District_Analysis/Resources/PCS_District%20Summary_2.png)

* How is the school summary affected?
  * Thomas High School saw a slight reduction in scores. See below. 
 
 * ### Original PyCity School Summary
![PCS_School_Summary_1](https://github.com/worksm/School_District_Analysis/blob/0c2252bb5e6743a775f0032ddcc5a4f0e06a4a2e/School_District_Analysis/Resources/PCS_School_Summary_1.png)

![PCS_School_Summary_2](https://github.com/worksm/School_District_Analysis/blob/37242cf421b8e4911240ce6e3bc593295654a322/School_District_Analysis/Resources/PCS_School_Summary_2.png)

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
 * Replacing the ninth graders' math and reading scores had no affect on Thomas High School's performance in relation to other schools. Even without the 9th grade scores, Thomas High School remained the second highest performing top school in the district. 

* How does replacing the ninth-grade scores affect the following:
 * Math and reading scores by grade are impacted in the data frame view. Thomas High School 9th grade field has a Nan value. 

 * ### Grades DF View
![PCS_Grades_Replace](https://github.com/worksm/School_District_Analysis/blob/58b2b725a09713db5c5c8980d0395a3410b257c1/School_District_Analysis/Resources/PCS_Grades_Replace.png)

* Scores by school spending, by school size, and school type weren't impacted in any meaningful way. When values were formatted to the nearest whole number, there weren't any value changes within the respective data frames. 

## Summary: 
Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

