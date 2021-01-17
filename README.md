# School_District_Analysis

## Overview

A city school district board requested analysis on the math and reading performance for high school students in the district along several metrics.  After I performed the initial analysis, evidence of academic dishonesty was discovered affecting reading and math grades for ninth grade students at one of the high schools, Thomas High School.  I removed the reading and math grades for all Thomas High School ninth graders, as can be seen in a section of the data below:

![removed scores](Resources/ths_ninth_removed.png)

This report details the differences when the analyses were performed again once the grades were removed.

- District Summary

  The total students and budget for the district were unaffected for the district, as students' grades were the only thing changed.  The average math grade and percentages of students passing math, reading, and overall all dropped slightly once the grades in question were removed, as can be seen below:
  
  - Original Analysis
 
  ![district original](Resources/district_orig.png)

  - Adjusted Analysis
 
  ![district updated](Resources/district_updated.png)

- School Summary
  
  Because Thomas High School was the only school to have grades removed, Thomas's results were the only ones to differ when breaking down grades and passing percentages by school.  Without the potentially false grades, Thomas's average scores for math and reading went down slightly, as did the percentages of students passing either subject and overall.
 
  - Original Analysis
 
  ![school original](Resources/school_orig.png)
 
  - Adjusted Analysis!
 
  ![school update](Resources/school_updated.png)

- Thomas High School's Relative Performance

  Thomas's ranking in overall performance among the high schools in the district did not change; they are the second ranked school.  Their overall passing percentage did drop much closer to the third ranked school once the questioned grades were removed.  It also worth noting that in reading performance, Thomas had been the top school, but fell to third in the adjusted analysis.

  - Original Analysis
 
  ![top 5 original](Resources/top_5_orig.png)

  - Adjusted Analysis
 
  ![top_5_updated](Resources/top_5_updated.png)

- Math and Reading Scores by Grade

  Analysis had been done to show the percentage of students in each grade level at each school passing each subject.  Because only Thomas High School ninth graders' scores were removed, the analysis for other schools, as well as for Thomas's other grade levels is unchanged.  The percent passing each subject for Thomas's ninth graders is simply a null value, as seen in the breakdowns for math here:

  - Original Analysis
 
    ![math by grade orig](Resources/math_by_grade_orig.png)

  - Adjusted Analysis
 
    ![math by grade update](Resources/math_by_grade_updated.png)

  Reading scores were similarly identical, with the exception of the null for Thomas's ninth graders.

- Scores by School Spending
  
  When analyzing performance based on the budget allocated for each student, the average grades and percentage of students passing dropped ever so slightly for schools allocating 630-644 per student (the spending range in which Thomas falls).  Other spending brackets are unchanged, as only grades in Thomas's bracket were adjusted.

  - Original Analysis
 
    ![spending unrounded orig](Resources/spending_unrounded_orig.png)

  - Adjusted Analysis
 
    ![spending unrounded update](Resources/spending_unrounded_updated.png)

  However, the changes are only by a miniscule amount to the raw percentages, and once the numbers are rounded in accordance with the district standards, there is no significant change:

  - Original Analysis
 
    ![spending rounded orig](Resources/spending_rounded_orig.png)

  - Adjusted Analysis
 
      ![spending rounded updated](Resources/spending_rounded_updated.png)

- Scores by School Size

  When analyzinge performance by school size, as with spending, any difference in the final metrics for Thomas's size (1,000 to 2,000 students) are negligible, and unchanged once rounded:

  - Original Analysis

    ![size rounded orig](Resources/size_rounded_orig.png)

  - Adjusted Analysis
 
    ![size rounded updated](Resources/size_rounded_updated.png)

- Scores by School Type

  When analyizing by school type, any differences in performance of charter schools (Thomas's type)are also negligible and unchanged once rounded.

  - Original Analysis
 
    ![type rounded orig](Resources/type_rounded_orig.png)

  - Adjusted Analysis
 
    ![type rounded updated](Resources/type_rounded_updated.png)

## Summary


