# School_Management
My First Project. This is a program meant to allow a user to manage the aspects of a high school, from the teacher, to the secretary and librarian

Requirements:
1) Latest Version of XAMPP running MYSQL and Apache on port 5511. The config files for both MYSQL and Apache are in the project folder under 'xammp config'
2) 'school_management' database, the data of which is kept in 'mysql' in the project folder.
3) Latest versions of java and python.


Functionality
* This project uses java as its backend, and python for its frontend. For Java, SpringBoot is used to create endpoints for users to inspect or manipulate data from the database. Note that the SpringBoot application is running on port 6970, but this can be changed in the application.properties file.
* For Python, Tkinter is used to code the GUI.


Explanation Of Methods:
1) Teacher:
   * Teachers are able to view students in their classes, view, add and alter their marks, view personal information of their students such as their class, age, parent or guardian        details like phone number, address and ID Number etc.

2) Secretary:
   * Secretaries are able to view students personal information on the system, add new students and staff members. They are also able to send emails (with and without attachments) to parents of students or otherwise. Secretaries are also able to view log entries of staff members into the system, alongside the date and time of their login or logout attempt.

3) Librarian:
   * Librarians are able to view books on the system, upload new books to the system, delete books, lend books out to students, view available (books that have not been issued) or unavailable (books that have been issued) books, as well as perform partial searches all library data using a search term. They can also search for specific genre's or authors of interest. 

NB: The viewing element of all users of the system works in two ways: with input taken and without. When input is taken, the data for the specific student or staff member or book is requested and displayed. When input is not supplied, all data pertaining to a particular search is requested and displayed.
