# PyCitySchools Challenge

## Overview of the School District Analysis
The purpose of this analysis was to rectify a previous school district analysis where the reading and math grades for Thomas High School ninth graders were potentially forged; although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards by replacing the math and reading scores for Thomas High School with 'NaN' values while keeping the rest of the data intact and then performing a school district analysis again on the modified data. The analysis was performed using the Pandas package and covered:
* Creating a district summary DataFrame;
* Creating a school summary DataFrame;
* Determining the top five performing schools based on the overall passing rates;
* Determining the bottom five performing schools based on the overall passing rates;
* Determining the average math scores for each grade level from each school;
* Determining the average reading scores for each grade level from each school;
* Determining the math and reading scores by school spending per student;
* Determining the math and reading scores by school size; and
* Determining the math and reading scores by school type.

## Results
Overall, it can be seen from the results below that the new DataFrames with the modified ninth grade scores for Thomas High School have not had a large impact on the results from our new analysis compared to the results from our previous analysis. We can compare the results from our original analysis with those from this new analysis by answering the questions below.

_____

### Old District Summary
![old_district_summary](https://user-images.githubusercontent.com/80941606/191794495-9c4eda0b-7fbf-41cb-9af1-ed9add05b3e7.png)

### New District Summary
![new_district_summary](https://user-images.githubusercontent.com/80941606/191794534-443f258f-f771-4121-ac97-38579f828051.png)

**Figure 1**: These are the district summaries determined from the old and new analysis scripts.

_____
* How is the district summary affected?
  * The average math score decreased by 0.1 and the passing percentages decreased by a similar amount after creating the new district summary. In otherwords, the changes made to the raw data did not have much of an impact on the analysis.

_____

### Old School Summary
![old_school_summary](https://user-images.githubusercontent.com/80941606/191837236-a37426e2-85dc-49dd-b195-12f99eb36227.png)

### New School Summary
![new_school_summary](https://user-images.githubusercontent.com/80941606/191837286-f059f59a-eb4b-4bf7-a21f-f5bd1a91d222.png)

**Figure 2**: These are the school summaries determined from the old and new analysis scripts.

_____

* How is the school summary affected?
  * The school summary was only impacted by changes made to the Thomas High School row since the ninth-grade scores from this school were dropped. In particular, the math and reading grades marginally decreased in the new analysis.

_____

### Old Top Five Schools
![old_top_schools](https://user-images.githubusercontent.com/80941606/191837449-b6bab5d4-b25c-41c7-938f-e6e5131d88b8.png)

### New Top Five Schools
![new_top_schools](https://user-images.githubusercontent.com/80941606/191837482-8f33a9e2-6136-4f33-ac90-f44066a1b889.png)

**Figure 3**: These are the top five schools summary determined from the old and new analysis scripts.

_____

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  * By removing the ninth-grade math and reading scores from Thomas High School, the high school's performance slightly increased in the new analysis. However, it retained its second-place ranking amongst the top five schools in the school's district.

_____

### Old Math Scores by Grade
![old_math_scores_by_grade](https://user-images.githubusercontent.com/80941606/191846445-43976bd8-fb00-406c-9229-12ab37875ff1.png)

### New Scores by Grade
![new_math_scores_by_grade](https://user-images.githubusercontent.com/80941606/191846498-6a103410-5ca2-4a5f-8ee2-4b78a21faef0.png)

### Old Reading Scores by Grade
![old_reading_scores_by_grade](https://user-images.githubusercontent.com/80941606/191846708-48d0b9c4-03e8-4dcc-b5f7-1821dcae34aa.png)

### New Reading Scores by Grade
![new_reading_scores_by_grade](https://user-images.githubusercontent.com/80941606/191846735-fc3adcd1-02f5-4ba1-bb09-c7e02644f07f.png)

### Old Scores by School Spending
![old_spending_summary](https://user-images.githubusercontent.com/80941606/191846801-e5129b77-3062-4fd4-b9f2-7563e69265e8.png)

### New Scores by School Spending
![new_spending_summary](https://user-images.githubusercontent.com/80941606/191846881-7701e4e4-38ab-4ad7-b4e1-724952c9510a.png)

### Old Scores by School Size
![old_scores_by_school_size](https://user-images.githubusercontent.com/80941606/191846910-334c299b-24dd-4b07-87aa-eec6c64c51ca.png)

### New Scores by School Size
![new_scores_by_school_size](https://user-images.githubusercontent.com/80941606/191846936-12e9a926-465b-4399-be2a-90583c1dd1b9.png)

### Old Scores by School Type
![old_scores_by_school_type](https://user-images.githubusercontent.com/80941606/191846980-302724ec-2bfb-4050-bb47-6923d10e7dc3.png)

### New Scores by School Type
![new_scores_by_school_type](https://user-images.githubusercontent.com/80941606/191847005-402615b1-c994-4f27-9b11-ce09126be367.png)

**Figure 4**: These are the math and reading scores by grade, school spending, school size, and school type.

_____
* How does replacing the ninth-grade scores affect the following?
  * Math and reading scores by grade:
    * The math and reading scores for the tenth, elventh, and twelfth grades remain the same in the new analysis as they were in the old analysis as expected.
  * Math and reading scores by school spending:
    * There are no discernable differences in the math and reading scores by school spending between the old and new analysis scripts.
  * Math and reading scores by school size:
    * There are differences in the math and reading scores by school size between the old and new analysis scripts, but these differences are neglible (e.g. differences in the tenths of a decimal number at most).
  * Math and reading scores by school type:
    * There are no discernable differences in the math and reading scores by school type between the old and new analysis scripts.

## Summary
In summary, the impact of removing the ninth-grade math and reading scores from Thomas High School from the analysis was neglible. However, the following four changes were noticed:
* The school district's average math and reading score decreased by a neglible amount;
* Thomas High School's math and reading scores slightly decreased;
* Thomas High School's performance slightly increased - but its ranking stayed the same - amongst the district's schools; and
* There was a neglible change in the math and reading scores by school size.
