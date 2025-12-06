📘 GradeBook Analyzer

A simple Python program to input student marks, calculate statistics, assign grades, and display results in a clean tabular format.


---

📌 Features

This program performs the following tasks:

1. Manual Student Data Entry

Enter the number of students

Enter each student’s name and marks


2. Statistical Analysis

The program calculates:

Average Marks

Median Marks

Highest Score

Lowest Score


3. Grade Assignment

Grades are assigned based on the following criteria:

Marks	Grade

90–100	A
80–89	B
70–79	C
60–69	D
Below 60	F


4. Pass / Fail Classification

Students scoring 40 or above → PASS

Students scoring below 40 → FAIL


5. Grade Distribution

Displays the total number of students in each grade.

6. Organized Output Table

A neatly formatted table showing:

Student Name

Marks

Assigned Grade



---

📂 Project Structure

GradeBook_Analyzer/
│
├── gradebook.py    # Main Python script
└── README.md        # Project documentation


---

▶ How to Run the Program

1. Make sure Python is installed on your system.


2. Save the code in a file named gradebook.py


3. Open a terminal/cmd and run:



python gradebook.py

4. Follow on-screen menu options.




---

🧠 Code Overview

Main Functionalities

Function	Purpose

calculate_average()	Calculates average of all marks
calculate_median()	Computes median value
find_max_score()	Finds highest mark
find_min_score()	Finds lowest mark
assign_grades()	Assigns grades to all students
pass_fail_students()	Creates pass/fail lists
display_results()	Displays final table of results
main()	Controls menu and workflow



---

📊 Sample Output

===== STATISTICAL ANALYSIS =====
Average Marks: 76.40
Median Marks: 75
Highest Marks: 95
Lowest Marks: 40

===== GRADE DISTRIBUTION =====
A: 2 students
B: 1 students
C: 1 students
D: 0 students
F: 0 students

===== PASS/FAIL SUMMARY =====
Passed (4): Akshay, Rohit, Sejal, Maya
Failed (0):


---

✔ Requirements

No external libraries needed.
Works on Python 3+


---

🙌 Author

Akshay Kumar
GradeBook Analyzer Project
