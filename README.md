# pandas-challenge

# PyCity Schools Analysis

## Overview

This project involves analyzing a dataset of school and student data for a city's school district. The goal is to aggregate the data and showcase trends in school performance based on standardized test results for math and reading. We use Python, Pandas, and Jupyter Notebook to complete the analysis, providing insights into district-wide and individual school performance.

## Dataset

The dataset includes two CSV files:

* **schools_complete.csv** : Information about each school, including school name, type, total students, and budget.
* **students_complete.csv** : Student information including name, gender, grade, math score, and reading score.

## Project Structure

* `PyCitySchools.ipynb`: The main Jupyter Notebook where the analysis is performed.
* `Resources/`: Folder containing the school and student dataset files.
  * `schools_complete.csv`
  * `students_complete.csv`
* `README.md`: The file you are currently reading, outlining the project.

## Analysis Tasks

1. **District Summary** :

* Total number of unique schools
* Total students
* Total budget
* Average math score
* Average reading score
* Percentage of students passing math
* Percentage of students passing reading
* Overall passing percentage (both math and reading)

1. **School Summary** :

* Key metrics for each school, including:
  * School name
  * School type
  * Total students
  * Total budget
  * Per student budget
  * Average math and reading scores
  * Percentage of students passing math, reading, and overall

1. **Top and Bottom Performing Schools** :

* Schools ranked by overall passing rate, displaying the top 5 and bottom 5 schools.

1. **Math and Reading Scores by Grade** :

* Analysis of math and reading scores for students by grade (9th, 10th, 11th, 12th) in each school.

1. **Scores by School Spending** :

* Schools categorized based on their per-student spending into bins, and performance compared in terms of math, reading, and overall passing percentages.

1. **Scores by School Size** :

* Schools categorized by size and analyzed in terms of test performance metrics.

1. **Scores by School Type** :

* Performance analysis based on whether a school is a district or charter school.

## Conclusion

The analysis provides valuable insights into the performance of schools across the district, including trends by spending per student, school size, and school type. Schools with higher spending do not necessarily perform better in terms of student test scores. Charter schools tend to perform better than district schools on average.

## Tools and Libraries Used

* **Python** : Main programming language used.
* **Pandas** : For data manipulation and analysis.
* **Jupyter Notebook** : For running and documenting the analysis.

## Resources and References

This project was completed using the following resources and references:

* [Pandas Documentation]()
* [Stack Overflow](https://stackoverflow.com/)
* [GeeksforGeeks](https://www.geeksforgeeks.org/)
