# School_District_Analysis
# Overview of the school district analysis: Explain the purpose of this analysis.
 The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.
 # Results: Using bulleted lists and images of DataFrames as support, address the following questions.
 # 1. How is the district summary affected?
  BEFORE:
    1) Average Math Score = 79.0
    2) Average Reading Score = 81.9
    3) % Passing Math 75
    4) % Passing Reading 86
    5) % Overall Passing 65
  AFTER:
    1) Average Math Score = 78.9
    2) Average Reading Score = 81.9
    3) % Passing Math 74.8
    4) % Passing Reading 85.7
    5) % Overall Passing 64.9
  
# 2. How is the school summary affected?  
BEFORE : % Overall Passing was 90
AFTER: % Overall Passing was 65

# 3.How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    Replacing ninth graders’ math and reading scores affect Thomas High School’s performance between the other schools, Relative ranking for Thomas High School changed from 2nd place to 8th 

# 4. How does replacing the ninth-grade scores affect the following:
    4.1 Math and reading scores by grade
          Math and Reading Scores from Thomas High School 9th Grade set to "nan" and equivalent to 0.
          Math and Reading Scores from Thomas High School 9th Grade means all of them failed (set to fail for analysis).
          Doing that, the only significantly score affected was minimal in a very small in quantity.
          Student count() Before: 1635
          Student count() After: 1174
    4.2 Scores by school spending
          Thomas HS is in the spending bucket "$630-644"
          Math and Reading Scores from Thomas High School 9th Grade means all of them failed (set to fail for analysis).
          Doing that, the only significantly score affected was minimal in a very small in quantity.
          Student count() Before: 1635
          Student count() After: 1174
    4.3 Scores by school size
          Removing Thomas High School 9th Grade reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for size bucket.
          Removing Students from Thomas High School 9th Grade reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for spending bucket "$630-644"
          Thomas High School is allocated on Spending Bin "$630-644" (image below)
    4.4 Scores by school type
          Thomas High School is in the "CHARTER" type
          Removing Thomas High School 9th Grade scores reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing"
          
          
# Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
 Changes that occurred is the number of total students, the number of students counted at Thomas High School, the average math and reading scores, and the overall percentages for math and reading at Thomas High School. For this analysis the removal of data implies a decrease in the count of total students overall, and total students at Thomas High School. And since the population amount was decreased, this leads to a change in average scores and score percentages. Due to the fact that these score and percentage changes were minimal, we can assume that the removal of math and reading scores of 9th graders at Thomas High School not as significant as we would imagine it to be.
 ![This is an image](https://github.com/olenarabani/School_District_Analysis/blob/main/Resources/Per_School_Summary_BEFORE.png)
 ![This is an image](https://github.com/olenarabani/School_District_Analysis/blob/main/Resources/Per_School_Summary_AFTER.png)
