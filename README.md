# PyCitySchools Challenge

## Overview of the School District Analysis
The purpose of this analysis was to rectify a previous school district analysis where the reading and math grades for Thomas High School ninth graders were potentially forged; although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards by replacing the math and reading scores for Thomas High School with 'NaN' values while keeping the rest of the data intact and then performing a school district analysis again. The analysis was performed using the Pandas package and covered:
* Creating a district summary DataFrame;
* Creating a school summary DataFrame;
* Determining the top 5 performing schools based on the overall passing rates;
* Determining the bottom 5 performing schools based on the overall passing rates;
* Determining the average math scores for each grade level from each school;
* Determining the average reading scores for each grade level from each school;
* Determining the scores by school spending per student;
* Determining the scores by school size; and
* Determining the scores by school type.

## Results
Overall, it can be seen from the results below that the new DataFrames with the modified 9th grade score for Thomas High School have not had a large impact on the results from our new analysis compared to the results from our previous analysis. We can compare the results from our original analysis with those from this new analysis by answering the questions below.

_____

### Old District Summary
![old_district_summary](https://user-images.githubusercontent.com/80941606/191794495-9c4eda0b-7fbf-41cb-9af1-ed9add05b3e7.png)

### New District Summary
![new_district_summary](https://user-images.githubusercontent.com/80941606/191794534-443f258f-f771-4121-ac97-38579f828051.png)

**Table 1**: These are the district summaries determined from the old and new analysis scripts.

_____
* How is the district summary affected?
  * The average math score decreased by 0.1 and the passing percentages decreased by a similar amount after creating the new district summary. In otherwords, the changes made to the raw data did not have much of an impact on the analysis.

_____

### Old School Summary
![old_school_summary](https://user-images.githubusercontent.com/80941606/191837236-a37426e2-85dc-49dd-b195-12f99eb36227.png)

### New School Summary
![new_school_summary](https://user-images.githubusercontent.com/80941606/191837286-f059f59a-eb4b-4bf7-a21f-f5bd1a91d222.png)

**Table 2**: These are the school summaries determined from the old and new analysis scripts.

_____

* How is the school summary affected?
  * The school summary was only impacted by changes made to the Thomas High School row since the 9th grade scores from this school were dropped.

_____

### Old Top 5 Schools
![old_top_schools](https://user-images.githubusercontent.com/80941606/191837449-b6bab5d4-b25c-41c7-938f-e6e5131d88b8.png)

### New Top 5 Schools
![new_top_schools](https://user-images.githubusercontent.com/80941606/191837482-8f33a9e2-6136-4f33-ac90-f44066a1b889.png)

**Table 3**: These are the top school summaries determined from the old and new analysis scripts.

_____

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  * By removing the 9th grade scores from Thomas High School, the high school's performance has increase by double-digit percentages.

_____

### Old Scores by Grade


### New Scores by Grade

### Old Scores by School Spending

### New Scores by School Spending

### Old Scores by School Size

### New Scores by School Size

### Old Scores by School Type

### New Scores by School Type

**Table 4**: These are the math and reading scores by grade, school spending, school size, and school type.

_____
* How does replacing the ninth-grade scores affect the following:
  * Math and reading scores by grade
    * 
  * Scores by school spending
    * 
  * Scores by school size
    * 
  * Scores by school type
    * 

## Summary
