SMART STUDENT RESULT AND ACADEMIC PERFORMANCE MANAGEMENT SYSTEM
Python + Tkinter + SQLite

FILES
-----
main.py             Start the application.
config.py           Database file path and grading configuration.
database.py         SQLite connection, table creation, and initial data.
models.py           Domain classes, validation, grade/SGPA/CGPA logic, and user roles.
analytics.py        Student-wise, subject-wise, semester-wise, class-wise and grade reports.
ui_helpers.py       Shared Tkinter forms, tables, buttons, and error handling.
people_frames.py    Student and faculty management screens.
academic_frames.py  Semester, subject, marks, results, analysis and student result screens.
app.py              Login window and main application.

RUN IN VS CODE
--------------
1. Extract the ZIP into a folder.
2. Open that folder in VS Code (File > Open Folder).
3. Open Terminal > New Terminal.
4. Run:
       python main.py
   If needed, use:
       py main.py

FIRST LOGIN
-----------
Username: admin
Password: admin123

DATABASE
--------
The file result_management.db is created automatically beside main.py.
Do not delete this file if you want to keep the records.

VS CODE DATABASE VIEWER
-----------------------
Install a SQLite extension from Extensions (Ctrl+Shift+X).
Open result_management.db using the extension to browse tables.

IMPORTANT
---------
This is a local desktop application using SQLite. The seeded admin password
is for initial project/demo use; change it before using real student data.
The grade scale and pass mark are configured in config.py.
