# Student Performance Tracker
This Python program is a basic Student Performance Tracking system. It allows users to enter students' names and their scores for various subjects, calculates the average score for each student, and determines if the student is passing or failing based on a minimum passing score. It also calculates and displays the class average.

## Features
1.Add Students: Enter the student's name and scores for subjects (Math, Science, English).

2.Calculate Student Average: Each student’s average score is calculated automatically.

3.Passing Status: Checks if each student meets the minimum passing score of 40 (default) for all subjects.

4.Calculate Class Average: Computes the average score of all students in the class.

5.Display Student Performance: Shows each student’s average score, passing status, and the overall class average.

6.Classes and Methods

### Student Class
1.__init__(self, name, scores): Initializes the student with a name and a list of scores.

2.calculate_average(self): Calculates and returns the average score for the student.

3.is_passing(self, passing_score=40): Checks if the student is passing all subjects with a score above or equal to the passing score.

#### PerformanceTracker Class
1.__init__(self): Initializes the class with an empty dictionary to store students.

2.add_student(self, name, scores): Adds a student to the tracker.

3.calculate_class_average(self): Calculates the overall class average score.

4.display_student_performance(self): Displays each student's average, passing status, and the class average.

##### Main Function
1.The main() function is the entry point of the program:

2.It continuously prompts for student names and scores until "done" is entered.

3.It then displays each student’s performance, including their average score and passing status, followed by the class average.

###### Usage
1.Run the Program: Execute the script with python filename.py.

2.Input Student Data:

3.Enter a student's name or type "done" to finish.

4.Enter scores for Math, Science, and English for each student.

5.Output: The program displays each student's average score, their passing/failing status, and the overall class average.
