# PyCity Schools Analysis

This assignment analyzes data from 15 schools across the district to uncover trends in school performance.

## Overview

This analysis uses school and student data to explore the relationship between various factors and student performance. It examines school performance based on:

- School type (Government vs. Independent)
- School size (Small, Medium, Large)
- Per student budget

The project includes the following files:

- `PyCitySchools.ipynb`: Jupyter Notebook containing the data analysis code and visualizations.
- `Module 4 Challenge Report.docx`: Report summarizing the analysis findings and conclusions.

## Analysis Summary

**Key Findings:**

- **School Performance:** Overall, students in the district demonstrated proficiency in both mathematics and reading, with average passing rates exceeding 80% for each subject.
- **School Budget vs. Performance:**  There was no strong correlation between per student budget and student performance. Schools in the lowest spending range performed comparably to those in higher spending brackets.
- **School Size vs. Performance:** Smaller schools (less than 1000 students) generally outperformed larger schools in terms of both average scores and passing rates.
- **School Type vs. Performance:** Independent schools consistently demonstrated higher average scores and passing rates compared to government schools. 

**Conclusions:**

The analysis suggests that school size and type may be more significant factors in student performance than per student budget. Smaller, independent schools tend to exhibit higher academic achievement. Further investigation is needed to understand the underlying factors contributing to these trends.

## Data

The analysis utilizes two CSV files located in the `Resources` folder:

- `schools_complete.csv`: Contains information about each school, including school name, type, size, and budget.
- `students_complete.csv`: Contains information about each student, including student ID, name, grade, school name, reading score, and math score.

## Dependencies

The analysis requires the following Python libraries:

- Pandas
- Pathlib

## How to Run the Analysis

1. Ensure the required dependencies are installed.
2. Open and run the `PyCitySchools.ipynb` Jupyter Notebook.
3. The notebook will generate the analysis results, including data tables and visualizations.
4. The `Module 4 Challenge Report.docx` provides a summary of the findings and conclusions.

