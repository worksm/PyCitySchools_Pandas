# School_District_Analysis
Analyzing PyCity school district utilizing Pandas. 
## Overview of the school district analysis:
The school district analysis aims to provide the client wiht a high-level overview of PyCity School Districts' key metrics, presented in a table format. The anaylsis also includes an overview of key metrics for each school, presented in table format. The final product for the client, was refactored to remove Thomas High School's 9th grade scores, due to fear of academic dishonesty. The district analysis provides a multifocal data analysis and comprehensive view in an end-user friendly format. 

## Results:
* ### How is the district summary affected?
 * The removal of Thomas High School's 9th grade students from the dataset had minimal impact on the district summary. In fact the original PyCity School District dataframe was formatted to match the updated dataframe and some values were rounded to the nearest tenth to illustrate the value shifts. See below. 

  * #### Original PyCity School District Summary

![PCS_District_Summary_1](https://github.com/worksm/School_District_Analysis/blob/70b122487fe070c1ad940565d68027b51125c04d/School_District_Analysis/Resources/PCS_District_Summary_1.png)

  * #### Updated PyCity School District Summary

![PCS_District_Summary_2](https://github.com/worksm/School_District_Analysis/blob/102b103ebe3f393a1bbeba57cc69a40eab6fea90/School_District_Analysis/Resources/PCS_District_Summary_2.png)

* How is the school summary affected?
  * Thomas High School saw a slight reduction in scores. See below. 
 
 * ### Original PyCity School Summary
![PCS_School_Summary_1](https://github.com/worksm/School_District_Analysis/blob/0c2252bb5e6743a775f0032ddcc5a4f0e06a4a2e/School_District_Analysis/Resources/PCS_School_Summary_1.png)

![PCS_School_Summary_2](https://github.com/worksm/School_District_Analysis/blob/37242cf421b8e4911240ce6e3bc593295654a322/School_District_Analysis/Resources/PCS_School_Summary_2.png)

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
 * Replacing the ninth graders' math and reading scores had no affect on Thomas High School's performance in relation to other schools. Even without the 9th grade scores, Thomas High School remained the second highest performing school in the district. 

* How does replacing the ninth-grade scores affect the following:
 * Math and reading scores by grade are impacted in the data frame view. Thomas High School 9th grade field has a Nan value. 

 * ### Grades DF View
![PCS_Grades_Replace](https://github.com/worksm/School_District_Analysis/blob/58b2b725a09713db5c5c8980d0395a3410b257c1/School_District_Analysis/Resources/PCS_Grades_Replace.png)

* Scores by school spending, by school size, and school type weren't impacted in any meaningful way. When values were formatted to the nearest whole number, there weren't any value changes within the respective data frames. 

## Summary: 
In summary, the removal of the Thomas High School ninth grade scores had minimal impact on outcomes. The biggest change was made to the dataset itself, utilizing the loc method to efficiently replace any 9th grade reading or math score with a value of "Nan". Thomas High School math scores and reading scores changed slightly.  

