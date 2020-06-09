# School_District_Analysis
## Project Overview
Analyzing school district test scores (math & reading) in an attempt to gain insight to their relation to a variety of factors. Steps included:
  - Cleaning student data by removing any professional prefixes or suffixes from names (ex:Dr,PH.D, etc.)
  - Generating summary statistics for the entire district.
  - Generating summary statistics for each school.
  - Finding which schools were high and low performing based on overall passing rates. 
  - Finding the average test scores by grade at each school.
  - Grouping schools by spending per student to see spending's relationship to average test performance.
  - Grouping schools by size to see size's relationship to average test performance.
  - Grouping schools by school type (district or charter) to see school type's relationship to average test performance.
  
## Challenge
There is evidence of academic dishonesty from the 9th graders at Thomas High School, and their scores must be replaced without removing them from the analysis. In this challenge, I replaced their math and reading scores with "NaN", and explored how this impacted all of the previous analysis. My findings are discussed below.

## Challenge Summary
*District Summary*:
   - The average math score for the district fell from 79.0 to 78.9 after removal of the fraudulent scores.
   - The average reading score for the district remained at 81.9.
   - The percentage of students passing math fell from 75.0% to 73.9%.
   - The percentage of students passing reading fell from 85.8% to 84.7%.
   - The overall passing percentage for the district fell from 65.2% to 64.1%.
  
*School Summary*:
   - The only school that was impacted by this removal of test scores was Thomas High School.
   - There was no change in the average math score of school.
   - The average reading score increased from 83.8 to 83.9.
   - The math passing rate fell from 93.3% down to 66.9%.
   - The reading passing rate fell from 97.3% to 70.0%.
   - The overall passing rate fell from 90.9% to 65.1%. 

*High/Low Performing Schools*:
   - Due to the redaction of test scores for ninth graders, Thomas High School went from being the 2nd best high school in the district      (by overall passing rate) to being the 7th best in the district.

*Test Scores by Grade*:
   - Due to the removal, the Thomas High School 9th grade average reading and math scores were changed to "NaN". All other scores            remained the same.

*Scores by School Spending*:
   - Thomas High School fell into the $630-644 spending per student category, so this was the only category impacted by the change.
   - For this category, the average reading and math scores stayed the same after the removal.
   - The percentage of students passing math in this category fell from 73% to 67%. 
   - The percentage of students passing reading in this category fell from 84% to 77%.
   - The overall passing rate of students in this category fell from 63% to 56%. 
   
*Scores by School Size*:
   - Thomas High School is a medium sized school (1,000 to 2000 students) so this was only size category that was impacted.
   - For this category, the average reading and math scores stayed the same after the removal.
   - The percentage of students passing math at medium sized schools fell from 94% to 88%.
   - The percentage of students passing reading at medium sized schools fell from 97% to 91%.
   - The overall passing rate for students at medium sized schools fell from 91% to 85%.

*Scores by School Type*:
   - Thomas High School is a charter school, so only this category was impacted by the score changes.
   - The average math and reading scores for charter schools remained the same.
   - The percentage of students passing math at charter schools fell from 94% to 90%.
   - The percentage of students passing reading at charter schools fell from 97% to 93%.
   - The overall passing percentage at charter schools fell from 90% to 87%.
   


  
   
  
    
   
