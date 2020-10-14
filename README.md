# School_District_Analysis
Test Score Analysis, Reporting & Presentation to provide insights about performance trends & patterns

## Overview of the School District Analysis
The aim of the School District Analysis was to accomplish a Math & Reading Test Score analysis for the district's school board to determine if the schools' budget, size and type have any effect on how the students perform in school on specific metrics.  Along the way, there were some anomolies discovered in the raw data students_complete.csv file, the test scores were altered for the Thomas High School 9th graders.  Another analysis was run after replacing those test scores with Nan until further investigation.  See below for details.

## Results
- District Summary Analysis
    - The analysis on the District level did not show any changes that were significant when the Thomas High School 9th grade class test scores were removed, as shown in the images below.\
**District Summary with Thomas High School 9th Grade Class**\
![alt text](https://github.com/ABonuan/School_District_Analysis/blob/main/Resources/District%20Summary%20with%20THS%209th%20Grade.png?raw=True)
\
**District Summary without Thomas High School 9th Grade Class**\
![alt text](https://github.com/ABonuan/School_District_Analysis/blob/main/Resources/District%20Summary%20without%20THS%209th%20Grade.png?raw=True)

- School Summary Analysis
    - Thomas High School Performance After Removing 9th Grade Information
        - Removing test scores from the analysis for Thomas High School 9th Grade class still did not pose any significant changes for the school.  The average Math & Reading scores, as well as the percentage of the passing students for each \(and\) both subjects went down slightly, but relatively stayed the same with only the scores from the 10th to 12th grade being considered.
        
        See images below for reference.\
        **School Summary with Thomas High School 9th Grade Class**\
        [School Summary with THS 9th Grade](https://github.com/ABonuan/School_District_Analysis/blob/main/Resources/School%20Summary%20with%20THS%209th%20Grade.png)
       
        **School Summary without Thomas High School 9th Grade Class**\
        [School Summary without THS 9th Grade](https://github.com/ABonuan/School_District_Analysis/blob/main/Resources/School%20Summary%20without%20THS%209th%20Grade.png) 

        - The key, but miniscule, differences before and after removing the supposed erroneous scores are:
            - Average Math Score: 83.4 vs 83.3
            - Average Reading Score:  83.8 vs 83.9

- Effect of Removing Thomas High School 9th Grade Class Test Scores on the following:
    - Math and Reading Scores by Grade - scores by grade are not affected since each grade is independent from each other.
    - Scores by School Spending, Size or Type were also not affected.


## Summary
In summary, the District & School Summary Analyses were minimally affected by removing the suspected erroneous score values for Thomas High School 9th Grade class.

From the overall School District Analysis, the students that perform well are from small to medium-sized charter schools.  Only one large-sized school made it to the top 5 performing schools, which was also a charter school.  The bottom 5 schools are all large-sized district schools.

Top 5 Performing Schools\
[Top 5](https://github.com/ABonuan/School_District_Analysis/blob/main/Resources/Top%205.png)

Bottom 5 Schools\
[Bottom 5](https://github.com/ABonuan/School_District_Analysis/blob/main/Resources/Bottom%205.png)
