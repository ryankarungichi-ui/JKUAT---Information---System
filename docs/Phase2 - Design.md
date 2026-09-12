PHASE 2: SYSTEM DESIGN

 1. Introduction

The design phase describes how the proposed JKUAT Information System will be organised and how the different users will interact with it.

2. System Architecture

The system will consist of the following main components:

- Student Portal
- Learning Management System (LMS)
- Lecturer Module
- Student Module
- Database

The Student Portal and LMS will share academic information through the system database.

3. Student Module

The student module will allow students to:

- Log into the system.
- Register units.
- View registered units.
- Access learning materials.
- View assignments and CATs.
- View marks and grades.

 4. Lecturer Module

The lecturer module will allow lecturers to:

- Log into the system.
- View assigned units.
- Upload notes.
- Create assignments.
- Create CATs.
- Enter student marks.

5. Unit Registration Design

The unit registration process will follow these steps:

1. Student logs into the Student Portal.
2. Student selects available units.
3. System checks the selected units.
4. The units are saved as registered units.
5. Registered units become available to the student on the LMS.

 6. Marks Management Design

The marks process will work as follows:

1. Lecturer logs into the LMS.
2. Lecturer selects an assigned unit.
3. Lecturer selects a student.
4. Lecturer enters assignment, CAT and examination marks.
5. System calculates the total mark.
6. Marks are stored in the database.
7. Student can view the marks through the Student Portal.

 7. Main Data Entities

The system will contain information about:

Student

- Student ID
- Name
- Password
- Registered units

Lecturer

- Lecturer ID
- Name
- Password
- Assigned units

Unit

- Unit code
- Unit name
- Lecturer

 Marks

- Student ID
- Unit code
- Assignment mark
- CAT mark
- Examination mark
- Total mark
- Grade

 8. User Interface Design

The system will use simple menus that allow users to select the operation they want to perform.

Main Menu

- Student Login
- Lecturer Login
- Exit

 Student Menu

- Register Unit
- View Registered Units
- View Marks
- Access LMS
- Logout

### Lecturer Menu

- View Units
- Upload Notes
- Create Assignment
- Create CAT
- Enter Marks
- Logout

9. Security Design

The system will use usernames/IDs and passwords to control access.

Students will only access student functions, while lecturers will access lecturer functions.

 10. System Flow

The overall system flow is:

Student Login
↓
Student Portal
↓
Register Units
↓
Units Available on LMS
↓
Lecturer Accesses LMS
↓
Lecturer Enters Marks
↓
Marks Stored
↓
Student Views Marks

11. Technology

The prototype will be developed using:

- C++
- Embarcadero Dev-C++
- GitHub

12. Conclusion

The proposed design provides a simple structure for managing students, lecturers, units and academic results. It also provides a connection between unit registration, the LMS and student results.
