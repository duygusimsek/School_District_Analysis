# School_District_Analysis

## Overview 

### History of the Analysis

In the previous project, a City School District requested an analysis based on the data collections from schools of the district and the students. 

The district-wide standardized test results for math and reading scores and the schools’ information (school types, school budget, etc. ) were analyzed. The analysis result will use for strategic decisions at the school and district levels regarding school budgets and priorities. 
[PyCitySchool.ipynb](https://github.com/duygusimsek/School_District_Analysis/blob/main/PyCitySchools.ipynb)

### Purpose of the Analysis

The school board had been discovered some alterations on the Thomas High School 9th grades math and reading scores and to ensure these altered scores do not skew the analysis, the Board request new data analysis with replacing the math and reading scores for 9th grade Thomas High School with null value while keeping the rest of the data untouched. 

## Results

Because of the new situation and change on the dataset, the school district analysis was needed to repeat and review how this change impacted the analysis result. [PyCitySchools_Challenge.ipynb](https://github.com/duygusimsek/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)

[Deliverable_1_result](https://github.com/duygusimsek/School_District_Analysis/blob/main/Screenshots/Deliverable_1_result.png)

### Impact on District Summary Analysis

Changing the Thomas High School 9th grade’s math and reading scores to NaNs did not make an important change on the District Analysis because the count of students from  Thomas High School 9th grade (461) only represents approximately 1.2% of the total student count (39,170) on the dataset. Because of that, the impact on the district analysis for each score had decreased by less than 0.03%. 

- [Previous District Analysis](https://github.com/duygusimsek/School_District_Analysis/blob/main/Screenshots/district_summary_originaln.png)
- [Recalculated District Analysis](https://github.com/duygusimsek/School_District_Analysis/blob/main/Screenshots/district_summary_with_NaNs.png)

### Impact on the School Summary Analysis

In the previous analysis, Thomas High School’s overall passing rate (math and reading) was over 91%.  Which was a high score among the other schools. But after adjusting the altered data had an important impact on Thomas High School’s overall passing rate, which had dropped to 65%.  
- [Previous School Summary Analysis - THS ](https://github.com/duygusimsek/School_District_Analysis/blob/main/Screenshots/THS_school_summary_original.png)
- [Recalculated School Summary Analysis - THS](https://github.com/duygusimsek/School_District_Analysis/blob/main/Screenshots/THS_school_summary_recalculated.png)

### Impact of adjusting data on Thomas High School Relative Performance to the Other Schools

The original analysis shows that with the 9th graders’ math and reading scores, Thomas High School ranked 2nd place in the “Top District School” list.   [Previous Top School List](https://github.com/duygusimsek/School_District_Analysis/blob/main/Screenshots/Original_top_schools.png)

After removing the 9th graders’ math and reading data, Thomas High School’s ranked in the “Top District School” list was not affected. Because the 9th-grade student count does not include the calculation of the new overall passing percentage, the changes only had a small impact of approximately a change of 1% point on each metric. [Recalculated Top School List](https://github.com/duygusimsek/School_District_Analysis/blob/main/Screenshots/Recalculated_top_schools.png)

### Impact of removing the 9th-grade scores on :

**1.Math and Reading Scores by Grade**

The only score that was affected on this DataFrame is the  9th-grade students at Thomas High School, which had  NaN instead of a grade for both math and reading scores.

- [Previous Math Score by Grade](https://github.com/duygusimsek/School_District_Analysis/blob/main/Screenshots/Original_math_score_by_grades.png)
- [Recalculated Math Score by Grade](https://github.com/duygusimsek/School_District_Analysis/blob/main/Screenshots/new_math_score_by_grades.png)
- [Previous Reading Score by Grade](https://github.com/duygusimsek/School_District_Analysis/blob/main/Screenshots/Original_reading_score_by_grades.png)
- [Recalculated Reading Score by Grade](https://github.com/duygusimsek/School_District_Analysis/blob/main/Screenshots/new_reading%20score_by_grades.png)

**2.Impact on Scores by School Spending**

The spending range where Thomas High School is located is $630-644 per student and it has a slight change which does not affect the result when the numbers were rounded up. 
- [Previous School Spending Summary](https://github.com/duygusimsek/School_District_Analysis/blob/main/Screenshots/Original_spending_summary.png)
- [Recalculated School Spending Summary](https://github.com/duygusimsek/School_District_Analysis/blob/main/Screenshots/Recalculated_spending_summary.png)

**3.Impact on Scores by School Size**

Because Thomas High School was grouped into Medium size schools, the medium-size category’s scores had less than 1% of change for each metric. 
- [Previous School Size Summary](https://github.com/duygusimsek/School_District_Analysis/blob/main/Screenshots/original_size_summary.png)
- [Recalculated School Size Summary](https://github.com/duygusimsek/School_District_Analysis/blob/main/Screenshots/Recalculated_size_summary.png)

**4.Impact on Scores by School Type**

District School types did not affect by the new data alteration. However,  because Thomas High School is a Charter type school slight changes had occurred. (less than 1%)
- [Previous School Type Summary](https://github.com/duygusimsek/School_District_Analysis/blob/main/Screenshots/Original_school_type_summary.png)
- [Recalculated School Type Summary](https://github.com/duygusimsek/School_District_Analysis/blob/main/Screenshots/Recalculated_school_type_summary.png)

## Summary

* Thomas High School’s overall passing rate had changed dramatically from 91% to 65%.
* Thomas High School's ranking for top schools had not been affected but the overall score was decreased slightly. 
* Thomas High School 9th-grade student math and reading data are not in the new dataset. 
* Charter schools’ success rate slightly affected.

## Resources 
* Data Sources: 
        [schools_complete.csv](https://github.com/duygusimsek/School_District_Analysis/blob/main/Resources/schools_complete.csv), 
        [students_complete.csv](https://github.com/duygusimsek/School_District_Analysis/blob/main/Resources/students_complete.csv)
* Software: [Jupiter Notebook 6.3.0](https://jupyter.org/)
* Language: [Python 3.10.2](https://www.python.org/downloads)
* Libraries: Pandas and Numpy
