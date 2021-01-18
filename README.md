# School_District_Analysis
# Analysis of School District Data
> Python script written & managed in Jupyter Notebook using PANDAS and Numpy libraries used to read, analyze, and output school, student, and district data. 

## Overview of School District Analysis
> Analysis conducted to create visualization of district-wide metrics. Evidence of scholastic dishonesty necessitated repeat analysis after data modification and comparison of the two data sets. 

### Results
> District Summary
![District Summary Original](Resources/district_anal1.png)
![District Summary Modified](Resources/district_anal2.png)
    - Slight decrease in average math score (.1)
    - No change in average reading score
    - Slight decrease in % passing math (.2)
    - Slight decrease in % passing reading (.3)
    - Slight decrease in overall passing (.1)

> School Summary
![School Summary Original](Resources/per_school1.png)
![School Summary Modified](Resources/per_school2.png)
    - Slight decrease in average math score (.067)
    - Slight increase in average reading score (.047)
    - Slight decrease in % passing math (.086)
    - Slight decrease in % passing reading (.29)
    - Slight decrease in % overall passing (.318)

> School Performance Ranking
![Top 5 Original](Resources/top_five1.png)
![Top 5 Modified](Resources/top_five2.png)
    - Thomas High School is ranked second for % overall passing both before and after removing the 9th grade students. 

> Math & Reading Scores by Grade
![Math Scores by Grade Original](Resources/mathByGrade1.png)
![Math Scores by Grade Modified](Resources/mathByGrade2.png)
![Reading Scores by Grade Original](Resources/readingByGrade1.png)
![Reading Scores by Grade Modified](Resources/readingByGrade2.png)
    - Since these data frames were already grouped by grade level, the only difference is the removal of the Thomas High School 9th grader scores which is replaced with 'nan'.

> Scores by School Spending
![Scores by Spending Original](Resources/spend1.png)
![Scores by Spending Modified](Resources/spend2.png)
    - There is no change to the scores based on per student spending.

> Scores by School Size
![Scores by School Size Original](Resources/size1.png)
![Scores by School Size Modified](Resources/size2.png)
    - There is no change to the scores based on size of school.

> Scores by School Type
![Scores by School Type Original](Resources/type1.png)
![Scores by School Type Modified](Resources/type2.png)
    - There is no change to the scores based on type of school. 

## Summary
> After analysis of the metrics related to student grades from before and after the removal of the 9th grade students the following noteworthy differences have been identified:
    - A decrease in the overall passing rate of Thomas High School students by .3%.
    - A decrease in the reading scores passing rate of .29% at Thomas High School and .3% for the entire district. 
    - A decrease in the math scores passing rate of .2% for the district. 
    - An increase in the average reading score for Thomas High School students of .047. 