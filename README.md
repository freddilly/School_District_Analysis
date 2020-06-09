# School_District_Analysis
## Project Overview
Analyzing school district test scores (math & reading) in an attempt to gain insight to their relation to a variety of factors. Steps included:
  - Cleaning student data by removing any professional prefixes or suffixes from names (ex:Dr,PH.D, etc.)
  - Generating summary statistics for the entire district.
  - Generating summary statistics for each school.
  - Finding which schools were high and low performing based on test scores. 
  - Finding the average test scores by grade.
  - Grouping schools by spending per student to see spending's relationship to average test performance.
  - Grouping schools by size to see size's relationship to average test performance.
  - Grouping schools by school type (district or charter) to see school type's relationship to average test performance.
  
## Challenge
There is evidence of academic dishonesty from the 9th graders at Thomas High School, and their scores must be replaced without removing them from the analysis. In this challenge, I replaced their math and reading scores with "NaN", and explored how this impacted all of the previous analysis. My findings are discussed below.

## Challenge Summary
  - *District Summary*:
    - The average math score for the district fell from 79.0 to 78.9 after removal of the fraudulent scores.
    - The average reading score for the district remained at 81.9.
    - The percentage of students passing math fell from 75.0% to 73.9%.
    - The percentage of students passing reading fell from 85.8% to 84.7%.
    - The overall passing percentage for the district fell from 65.2% to 64.1%.

  - *School Summary*:
   - 
