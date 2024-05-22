In this project, I have created a simple Quiz Application using Python and the tkinter library. This application provides users with the ability to sign in as either administrators or students, take quizzes, and manage quiz questions. 
Project Components:
1. Module Imports:
We begin by importing the necessary Python modules, including tkinter for the graphical user interface, ttk for themed widgets, and messagebox for displaying messages to the user.
2. Data Storage:
We define a Python list called 'quiz_data' to store quiz questions and their options. Each question is represented as a dictionary.
3. User Authentication:
We manage user authentication through two dictionaries, 'admindict' and 'studentdict,' which store usernames and passwords for administrators and students.
4. Main Application Window:
We create the main root window for our application, setting its size and title to provide a user-friendly interface.
5. Sign-In Window:
The Sign-In window is implemented as a Toplevel widget.
Users can enter their username and password in this window.
Checkbuttons are used to select whether the user is an admin or a student.
The 'validate_credentials' function checks the entered credentials' validity and opens the respective window (admin or student) based on the user type.
6. Admin Window:
In the admin window, administrators have the ability to add and delete quiz questions.
An 'Add Question' button allows administrators to input questions, options, and the correct answer, which are then added to the 'quiz_data' list.
A 'Delete Selected Question' button removes the currently selected question from the list.
7. Student Window:
In the student window, students can start taking the quiz.
Clicking the 'Start' button triggers the 'Quiz' function, initiating the quiz.
The 'Quiz' function presents one question at a time, enabling students to select an answer. Immediate feedback is provided to inform students whether their answer is correct or not.
The score is continuously calculated as students answer questions, and a final score is displayed at the quiz's conclusion.

This is a basic yet functional quiz application that can be customized and expanded upon to suit various educational or testing needs.The changes such as, using a file to store the data makes it more functionable.
