# School_District_Analysis

## Overview of School District Analysis
A school board detects evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders which appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, and to uphold state-testing standards, this analysis will:

 * Replace ninth-grade reading and math scores with NaNs while keeping the data intact.
 * Summarize district metrics
 * Summarize school metrics
 * The average math score for each grade level from each school.
 * The average reading score for each grade level from each school.
 * The scores by school spending per student, by school size, and by school type.

## Resources
-Data Source: Resources/schools_complete.csv, Resources/students_complete.csv

-Software: Jupyter Notebook

## Results 
Before the data clean up, the total student count was 39,170; after the data clean up (replaced ninth-grade reading and math scores with NaNs) the new total student count is 38,709.

The district summary shows 

![Resources/initial_school_district_summary.png](Resources/initial_school_district_summary.png)

![Resources/district_summary.png](Resources/district_summary.png) 

*How is the school summary affected?

![Resources/School_Summary.png](Resources/School_Summary.png) 

*How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

*How does replacing the ninth-grade scores affect the following:

  *Math and reading scores by grade
  
  ![Resources/math_scores_by_grade.png](Resources/math_scores_by_grade.png)
  
  ![Resources/reading_scores_by_grade.png](Resources/reading_scores_by_grade.png)
  
  *Scores by school spending
  
  ![Resources/scores_by_school_spending.png](Resources/scores_by_school_spending.png)
  
  *Scores by school size
  
  ![Resources/scores_by_school_size.png](Resources/scores_by_school_size.png)
  
  *Scores by school type
  
  ![Resources/scores_by_school_type.png](Resources/scores_by_school_type.png)
  
## Summary 
Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
