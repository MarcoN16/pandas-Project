# pandas-challenge

# School District Analysis Report

This project use Pandas and Jupyter Lab to create an in-depth report for the city's school district. The analysis aims to assist the school board and mayor in making informed decisions regarding future school budgets and priorities.

# Description of Observable trend

The analysis highlights similar average scores in math and reading across the school district. However, there's a notable discrepancy in the percentage of students passing these subjects. While the passing rate for math stands at 75%, the passing rate for reading is notably higher at 82%. The overall passing rate for both subjects hovers around 65% for the district. Upon examining the highest-performing schools, it's evident that all top-ranking schools are charter schools. These top five schools boast an impressive overall passing rate of 91%, with nearly identical passing rates for math (94%) and reading (97%). Conversely, the lowest-performing schools exclusively belong to the district, reflecting a stark contrast with an overall passing rate of 53%. Among these schools, there's a higher percentage of students passing reading (81%) compared to math (66%). This analysis underscores the stark contrast between charter and district schools. Charter schools exhibit educational programs tailored to meet individual student needs and goals. In contrast, district schools adhere to more stringent rules dictating curriculum and standards across all institutions. The overall analysis emphasizes a significant performance gap between Charter schools (overall passing = 90%) and district schools (overall passing = 54%), with district schools particularly impacted in math passing percentage (67%).

An insightful observation arises from an in-depth analysis of spending ranges per student. Surprisingly, an inverse relationship emerges between the overall passing percentage and the expenditure per student. Higher spending does not necessarily correlate with improved performance. Additionally, grouping schools by size reveals that larger schools demonstrate poorer performance (Large school % Overall Passing = 58%, Small school % Overall Passing = 90%).

In summary, the analysis pinpoints a lower math score compared to reading, influencing the overall passing metric. District schools exhibit lower passing percentages compared to charter schools. Notably, larger schools tend to exhibit lower performance. Interestingly, both school types show a similar range of spending per student, yet higher spending does not guarantee better-passing percentages. Further investigation is crucial to comprehend this phenomenon and its implications.



# Data Sources

The analysis integrates information from two CSV files: schools_complete.csv and students_complete.csv. The merged dataset includes crucial details such as:

    School ID, school_name, type, size, budget from schools_complete.csv
    Student ID, student_name, gender, grade, school_name, reading_score, math_score from students_complete.csv

# Analysis Overview

District Summary

This section presents key metrics for the entire district:

- Total number of unique schools
- Total number of students
- Total budget
- Average math and reading scores
- Percentage of students passing math, reading, and both subjects (overall passing percentage)

![District_summary](https://github.com/MarcoN16/pandas-challenge/assets/150491559/a6075193-19c0-473b-a82c-c5017c511486)

School Summary

The school-specific metrics include:

- School name
- School type
- Total students
- Total school budget
- Per student budget
- Average math and reading scores
- Percentage of students passing math, reading, and both subjects

  ![School_Summary](https://github.com/MarcoN16/pandas-challenge/assets/150491559/8beec4d0-60bc-41d4-8822-ded079002c16)


Performance Analysis

- Highest and Lowest-Performing Schools (by % Overall Passing)
- Average math and reading scores for each grade level (9th, 10th, 11th, 12th) at each school
  
Highest:
![Highest-Performing_Schools](https://github.com/MarcoN16/pandas-challenge/assets/150491559/685f0d34-b232-4b0a-b957-2d080c33bbf2)

Lowest:
![Bottom_Performing_Schools](https://github.com/MarcoN16/pandas-challenge/assets/150491559/69ae7321-8069-4f11-8bf0-f05c69b67e5b)

Average math scores
![Math Scores by Grade](https://github.com/MarcoN16/pandas-challenge/assets/150491559/bf2f9e3e-fabc-411c-9b5e-bcb5807b1618)

Average reading scores
![Reading Score by Grade](https://github.com/MarcoN16/pandas-challenge/assets/150491559/21ca3049-520b-4a04-8875-1660517c9cdb)


Metrics by Spending Ranges

This table breaks down school performance based on average spending ranges per student. It includes:

- Average math and reading scores
- Percentage of students passing math, reading, and both subjects

![Scores by School Spending2](https://github.com/MarcoN16/pandas-challenge/assets/150491559/0e28b766-96c7-4b95-a4bd-aa155eee251a)


Metrics by School Size

- Summarizes key metrics based on school size.

![Scores by School Size2](https://github.com/MarcoN16/pandas-challenge/assets/150491559/bf8b9fbf-0e6b-49bb-a49c-8342544e4ec6)


Metrics by School Type

- Summarizes key metrics categorized by school type (Charter vs. District).

![Scores by School Type](https://github.com/MarcoN16/pandas-challenge/assets/150491559/06a305e1-a26d-41fd-ba7f-458be7397772)
