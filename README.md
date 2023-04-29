# Library Management System in C++
# Project Overview:
The Library Management System is a console-based application developed in C++ that allows admins and students to manage library resources effectively. The system enables students to access the library data by registering or logging in to their accounts. Admins have the ability to manage the books and students' accounts. The system supports adding, editing, and viewing books, as well as managing student accounts, issuing books, and handling fines.

# Key Features:
User Authentication: The system provides a login option for both admins and students, protected by a password.

# Admin Functions:
  a. Add a book to the system: The admin can add new books to the library.
  b. Edit the details of the book: The admin can edit the title and author of a book using its ISBN number.
  c. View the status of books: The admin can view the list and availability of books in the library.
  d. View enrolled students: The admin can view the list of students registered in the system, sorted by their roll numbers.
  e. View student balance: The admin can view the account balance of a specific student.

# Student Functions:
  a. Create an account: A new student can register by providing their roll number, name, and initial deposit.
  b. View balance: Students can view their account balance.
  c. Deposit amount: Students can deposit money into their accounts.
  d. Issue a book: Students can issue books from the list of available books.

Account management: The system supports up to 20 students, who pay $20 for account opening and $30 as a security deposit. Students can issue any book for $2 for a 10-day period. Fines are imposed for late returns as per the specified rules.

Data storage: The system uses 2D arrays to store the details of students and books. Initially, 15 books are stored in the library. Each student account contains the roll number, balance, and first name.

# Implementation Details:
The application is implemented in C++ without using classes, pointers, or structures. It employs 2D arrays, functions, loops, if-else, and switch operators to achieve the desired functionality. The main() function handles user inputs, presents options to the user, and calls appropriate functions based on the selected options. The program runs in a loop until the user decides to exit.

This project is suitable for students who have completed a Programming Fundamentals course or lab and want to demonstrate their skills in C++ programming without using advanced concepts like classes or pointers. It provides a solid foundation for further learning and improvement in C++ and software development.
