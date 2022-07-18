# School_District_Analysis

## Project Overview
The school board requires a redo of the school district analysis due to evidence of potential academic dishonesty regarding the Thomas High School ninth grade reading and math grades. For the time being we will be replacing the reading and math grades for the ninth graders at Thomas High School with "NaN's" until further notice. 

## Resources
-   Data source: schools_complete.csv, students_complete.csv
-   Software: Python 3.9.12 

## Results
- How is the district summary affected?
    - The district data is hardly affected, at most a few hundreth of a percent. Once values are formatted there is no change to the district data.
    
- How is the school summary affected?
    - As follows the school summary was barely affected. Change is seen on a scale of hundreths.

Here we see the original per school summary (top)
![Per School Summary Original](https://github.com/nfujikad/School_District_Analysis/blob/main/Resources/THS_orig_per_school_summary.png)

Here we see the new per school summary (top)
![Per School Summary New](https://github.com/nfujikad/School_District_Analysis/blob/main/Resources/THS_new_per_school_summary.png)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    -Thomas High School still scored second best in math and reading compared to the other schools.

How does replacing the ninth-grade scores affect the following:

Math and reading scores by grade
    - The only score affected by this change is the ninth grade score for Thomas High School. All other grades for corresponding school are unaffected since the data shows the scores per grade per school. 
Scores by school spending
    - This was unchanged 
Scores by school size
    - This was unchanged
Scores by school type
    - This was unchanged

## Summary
With respect to the large data set, the ninth grade class at Thomas High School is not large enough to significantly skew the analysis. 
