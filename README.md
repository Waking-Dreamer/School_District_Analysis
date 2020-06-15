# School_District_Analysis_Challenge

Versions:
- Python 3.7.7
- Matplotlib 3.1.3

## Overview

After learning that the Thomas High School 9th grader’s test scores were altered, they were removed from the calcualtions. Below is a summary of how this change impacted the final reading and math scores at several different levels:

### District Summary Impact:
Changing the Thomas High School 9th grader’s test scores to NaN had a very minor impact on the District Summary DataFrame. The average math score dropped from 79 to 78.9. The average reading score was not impacted. The passing math score percentage changed from 75% to 74% and the passing reading score percentage also changed 1% from 86% to 85%. The overall passing percentage also dropped from 65% to 64%.

### School Summary Impact:
Changing the Thomas High School 9th grader’s test scores to NaN has a far greater impact on the School Summary DataFrame in some areas. For Thomas High School, the average math score slightly dropped from 83.41 to 83.35 and the average reading score slightly increased from 83.84 to 83.89. The percent of students that passed math greatly decreased from 93.3% to 66.9%. The percent of students that passed reading also dropped from 97.3% to 69.7%. The overall passing percentage, for Thomas High School, was also impacted as it dropped from 90.9% to 65.1%.

### Impact on High & Low Performing Schools:
Before the Thomas High School 9th grader’s test scores were removed, Thomas High School was ranked in second place as a high performing school with the overall passing percentage of 90.9%. After the 9th grader’s test scores were removed, Thomas High school dropped to 8th place with the overall passing percentage of 65.1%.

### Impact on Math and Reading Scores by Grade:
Given that only the 9th grader’s test scores were removed, there was no impact to other grade levels. The only thing that changed is that NaN is now displayed in the 9th grade column, for Thomas High School, for both the Math and Reading scores. 

### Impact on Scores by School Spending:
Thomas High School falls in the $630 - $644 spending range. This means all other spending ranges were not impacted. For the $630 - $644 spending range, the average math score (78.5) and reading score (81.6) did not change. The percent of students that passed Math dropped from 73% to 67% and the percent of students that passed reading dropped from 84% to 77%. The overall passing percentage dropped from 63% to 56%.

### Impact on Scores by School Size:
Thomas High School falls in the medium school size range. This means the other school size ranges were not impacted. For the medium school size range, the average math score (83.4) and reading score (83.9) did not change. The percent of students that passed Math dropped from 94% to 88% and the percent of students that passed reading dropped from 97% to 91%. The overall passing percentage dropped from 91% to 85%.

### Impact on Scores by School Type:
Thomas High School is a charter school, therefore the district school type was not impacted. For the charter school type, the average math score (83.5) and reading score (83.9) did not change. The percent of students that passed Math dropped from 94% to 90% and the percent of students that passed reading dropped from 97% to 93%. The overall passing percentage dropped from 90% to 87%.