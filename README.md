# pandas-challenge
## Challenge chosen: PyCitySchools
This Jupyter Notebook takes in CSVs about students, their grades, and their schools in a district and provides reporting. CSVs are:
* PyCitySchools/Resources/students_complete.csv
* PyCitySchools/Resources/schools_complete.csv

Analysis file:
* PyCitySchools/04-Pandas_Homework_PyCitySchools_PyCitySchools_ch.ipynb

<br>--------------------------------------------------------------------------------------------
<br>**OBSERVATIONS:**
1. I found it interesting that charter schools wholly outperformed district schools
1. It was also interesting to see that per-student budgets don't translate to better scores. In fact, in every case, the budget per student was the opposite of what I initially expected.
1. This made me curious, so I added another analysis that broke down type of school by per-student budget and found that, on average, charter schools had less budget per student than district schools. ($599.50 vs $643.57, respectively).
1. Based on all of this data, I have to conclude that there are other factors at play here beyond a crude overall budget-to-student relationship. For example, we don't know anything about teachers, class size, or attendance. And we don't know anything about the students' background, like household income, number of parents present, amount of out-of-school tutoring, demographics, etc. There's a lot going on when you talk about schools, grades, and budgets that aren't captured in the limited data we have here.

<br>--------------------------------------------------------------------------------------------

## Reports in file:

### District Summary
A high-level snapshot of the district's key metrics, including:
* Total Schools
* Total Students
* Total Budget
* Average Math Score
* Average Reading Score
* % Passing Math (The percentage of students that passed math.)
* % Passing Reading (The percentage of students that passed reading.)
* % Overall Passing (The percentage of students that passed math and reading.)

### School Summary
A summary of key metrics about each school, including:
* School Name
* School Type
* Total Students
* Total School Budget
* Per Student Budget
* Average Math Score
* Average Reading Score
* % Passing Math (The percentage of students that passed math.)
* % Passing Reading (The percentage of students that passed reading.)
* % Overall Passing (The percentage of students that passed math and reading.)

### Top Performing Schools (By % Overall Passing)
Top 5 performing schools based on % Overall Passing. Include:
* School Name
* School Type
* Total Students
* Total School Budget
* Per Student Budget
* Average Math Score
* Average Reading Score
* % Passing Math (The percentage of students that passed math.)
* % Passing Reading (The percentage of students that passed reading.)
* % Overall Passing (The percentage of students that passed math and reading.)

### Bottom Performing Schools (By % Overall Passing)
Bottom 5 performing schools based on % Overall Passing.
This includes all of the same metrics as above.

### Math Scores by Grade
Average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade
Average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending
School performance based on average Spending Ranges (Per Student). Data is broken down by ranges (<$584, $585-629, $630-644, and $645-675).
* Average Math Score
* Average Reading Score
* % Passing Math (The percentage of students that passed math.)
* % Passing Reading (The percentage of students that passed reading.)
* % Overall Passing (The percentage of students that passed math and reading.)

### Scores by School Size
School performance based on school size (Small, Medium, Large), (<1000, 1000-2000, and 2000-3000>)

### Scores by School Type
School performance based on school type (Charter vs. District).

### Extra analysis: Per-student budget by school type
Budgets per student based on school type (Charter vs. District).