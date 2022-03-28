# School_District_Analysis

## Overview 

### History of the Analysis

In the previous project, a City School District requested an analysis based on the data collections from schools of the district and the students. (add the data sources here). (school_data and student_data)

The district-wide standardized test results for math and reading scores and the schools’ information (school types, school budget, etc. ) were analyzed. The analysis result will use for strategic decisions at the school and district levels regarding school budgets and priorities. (add the “PyCitySchool.ipynb” here)

### Purpose of the Analysis

The school board had been discovered some alterations on the Thomas High School 9th grades math and reading scores and to ensure these altered scores do not skew the analysis, the Board request new data analysis with replacing the math and reading scores for 9th grade Thomas High School with null value while keeping the rest of the data untouched. 

## Results

Because of the new situation and change on the dataset, the school district analysis was needed to repeat and review how this change impacted the analysis result. 

### Impact on District Summary Analysis

Changing the Thomas High School 9th grade’s math and reading scores to NaNs did not make an important change on the District Analysis because the count of students from  Thomas High School 9th grade (461) only represents approximately 1.2% of the total student count (39,170) on the dataset. Because of that, the impact on the district analysis for each score had decreased by less than 0.03%. 

Previous District Analysis(add the screenshot here)-or the link
Recalculated District Analysis(add the screenshot here)

### Impact on the School Summary Analysis




## Resources 
* Data Sources: 
        [schools_complete.csv](https://github.com/duygusimsek/School_District_Analysis/blob/main/Resources/schools_complete.csv), 
        [students_complete.csv](https://github.com/duygusimsek/School_District_Analysis/blob/main/Resources/students_complete.csv)
* Libraries: Pandas and Numpy
* Software: [Jupiter Notebook 6.3.0](https://jupyter.org/)
* Language: [Python 3.10.2](https://www.python.org/downloads)
