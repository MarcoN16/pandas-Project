# pandas-challenge

# School District Analysis Report

This project use Pandas and Jupyter Lab to create an in-depth report for the city's school district. The analysis aims to assist the school board and mayor in making informed decisions regarding future school budgets and priorities.

# Description of Observable trend

The analysis covers 15 schools with a collective student count of 39,170. Across the entire school district, similar average scores in math and reading were observed. However, there's a significant gap in the percentage of students passing these subjects. Math demonstrates a passing rate of 75%, while reading boasts a notably higher rate of 82%. The overall passing rate for both subjects hovers around 65% for the district. Upon scrutinizing the highest-performing schools, a notable trend emerges—all top-ranking schools belong to the charter category. These top five schools exhibit an impressive overall passing rate of 91%, showcasing nearly identical passing rates for math (94%) and reading (97%). In stark contrast, the lowest-performing schools exclusively belong to the district, reflecting an overall passing rate of 54%. Among these schools, there's a higher percentage of students passing reading (81%) compared to math (66%). Specifically, Rodriguez High School has the lowest overall passing percentage (53%), while Cabrera High School boasts the highest (91%). The analysis underscores the vast contrast between charter and district schools. Charter schools adopt tailored educational programs to address individual student needs and goals. Conversely, district schools operate under more rigid curriculum and standards across all institutions. This could delineate a significant performance gap between charter schools (overall passing = 90%) and district schools (overall passing = 54%).

An intriguing insight from an in-depth analysis of spending ranges per student reveals an unexpected pattern—an inverse relationship exists between overall passing percentage and expenditure per student. A higher spending range per student does not necessarily translate to enhanced performance. Additionally, segregating schools by size unveils that larger schools demonstrate comparatively poorer performance (Large school % Overall Passing = 58%, Small school % Overall Passing = 90%).

In summary, the analysis underscores a noticeable difference between math and reading scores, significantly impacting the overall passing rate. Notably, no significant differences emerged from the math and reading scores across each grade level (9th, 10th, 11th, 12th) in all schools. However, district schools consistently exhibit lower passing percentages compared to charter schools, potentially influenced by the notably higher student count in district schools (district vs charter = 26,976 vs 12,194) and more rigid curriculum and standards. Notably, larger schools tend to exhibit lower performance, signifying a crucial area for improvement to elevate overall passing rates in such institutions. Therefore, educational authorities should focus on managing student size in schools and classes, as it significantly influences student achievement. Intriguingly, both school types display a similar spending range per student, despite higher spending not guaranteeing improved passing percentages. This phenomenon warrants comprehensive investigation to discern its implications comprehensively.




# Data Sources

The analysis integrates information from two CSV files: schools_complete.csv and students_complete.csv. The merged dataset includes different information such as:

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

Average math scores:

![Math Scores by Grade](https://github.com/MarcoN16/pandas-challenge/assets/150491559/bf2f9e3e-fabc-411c-9b5e-bcb5807b1618)

Average reading scores:

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
