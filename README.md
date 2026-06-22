Student Grade Calculator
1. Project Overview and Objectives
This project is a Python-based Student Grade Calculator that accepts student marks, calculates grades, and displays the corresponding result. The project demonstrates the use of decision-making statements (if-elif-else), functions, user input, and loops.
Objectives
Calculate grades based on marks.
Practice Python decision-making statements.
Understand functions and code organization.
Display meaningful output to users.
2. Setup and Installation Instructions
Prerequisites
Python 3.x installed on your system.
Steps to Run
Install Python from the official website.
Save the program as grade_calculator.py.
Open Terminal/Command Prompt.
Navigate to the project folder.
Run the program:
python grade_calculator.py
3. Code Structure Explanation
Function Used
def calculate_grade(marks):
This function determines the grade based on the marks entered by the user.
Decision Making Logic
if marks >= 90:
    grade = "A"
elif marks >= 75:
    grade = "B"
elif marks >= 60:
    grade = "C"
else:
    grade = "D"
The program checks marks against predefined conditions and assigns a grade accordingly.
User Input
marks = int(input("Enter marks: "))
Allows users to enter marks.
Output
print("Grade:", grade)
Displays the calculated grade.
4. Screenshots of Working Application
Add screenshots showing:
Program execution.
Input of marks.
Display of grades.
Different test cases.
Example:
Marks: 95 → Grade A
Marks: 82 → Grade B
Marks: 65 → Grade C
Marks: 45 → Grade D
5. How Technical Requirements Were Met
✅ Used if-elif-else statements for grading logic.
✅ Used a function (calculate_grade) to organize code.
✅ Accepted user input using input().
✅ Displayed results using print().
✅ Followed Python programming standards and readable code structure.# student-grade-calculator
