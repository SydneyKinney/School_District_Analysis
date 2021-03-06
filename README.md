# School_District_Analysis
## Overview
The students_complete.csv file showed evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. The goal is to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once the math and reading scores have been replaced, the school district analysis was repeated.
## Results
### - How is the district summary affected?

The total count of students did not change. There were minimal changes when comparing the two charts. For example, the overall passing percentage would be the same number if rounded to the nearest whole number on both charts. The same applies to average math scores, average reading score, percentage passing math, and percentage passing reading. 

Original district analysis:
![Screen Shot 2022-07-08 at 2 48 59 PM](https://user-images.githubusercontent.com/107209737/178075213-8ae3ff94-4c0b-4903-9c60-1680756092e6.png)

Updated district analysis:
![Screen Shot 2022-07-08 at 2 48 03 PM](https://user-images.githubusercontent.com/107209737/178075225-83571e5f-a697-4e9f-94ef-79f022de1bbc.png)

### - How is the school summary affected?

Thomas High School originally had a 91% passing rate. After updating the analysis, Thomas High School had a passing rate of 65%. Replacing the math and reading scores with NaNs significantly affected the school summary. 

Original district analysis:
![Screen Shot 2022-07-08 at 3 09 13 PM](https://user-images.githubusercontent.com/107209737/178076839-1e8bba3c-a6fe-467c-99d5-75e523c90ce5.png)
<img width="1076" alt="Screen Shot 2022-07-08 at 3 13 50 PM" src="https://user-images.githubusercontent.com/107209737/178076852-c9907284-9956-4202-899c-deabd640bde6.png">

Updated district analysis:
![Screen Shot 2022-07-08 at 3 09 13 PM](https://user-images.githubusercontent.com/107209737/178076762-201acb06-5504-44f7-b9b4-439f0fbd8502.png)
![Screen Shot 2022-07-08 at 3 09 22 PM](https://user-images.githubusercontent.com/107209737/178076779-6fe6abea-db19-4025-9fbc-6a1f1a8afe6d.png)


### - How does replacing the ninth graders??? math and reading scores affect Thomas High School???s performance relative to the other schools?

Thomas High School was originally ranked 2nd for the percentage of overall passing. However, after running the updated analysis,  there was a significant drop in passing rate and Thomas High School is no longer ranked 2nd compared to the other schools. Thomas High School is now ranked one of the lowest schools in comparison to the other schools.

### - How does replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade:
The original analysis showed that Thomas High School had a 83.6 math average and a 83.7 reading average for the 9th grade tests. Now the scores have been replaced with null values and shows up as NaN in the following charts.

Math Average Image(below)

![Screen Shot 2022-07-08 at 3 33 11 PM](https://user-images.githubusercontent.com/107209737/178078433-392b419d-106f-4c6e-9bf5-c3f7c02bf964.png)

Reading Average Image(below)

![Screen Shot 2022-07-08 at 3 33 22 PM](https://user-images.githubusercontent.com/107209737/178078440-c63075de-b094-4152-bb4e-1631b44e05f3.png)


#### Scores by school spending, scores by school size, and scores by school type:
There was very little impact regarding school spending, school size, and school type. The numbers would be the same if rounded to the whole number in the original data and updated data. The only changes that occured from the original data to the updated data were shown in the hundredths place. 

 
## Summary
After replacing the math and reading scores for Thomas High School with NaNs, the overall passing rate changed drastically from 91% to 65% and the schools ranking dropped. The data for the 9th grade Thomas High School students will now show "NaN." There were changes in the overall passing rate, the math averages, and the reading averages. However, the impacts were minimal regarding school spending, school size, and school type.
