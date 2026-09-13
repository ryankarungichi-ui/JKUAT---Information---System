PHASE 3: PROGRAMMING

1. Introduction

The programming phase involves implementing the proposed JKUAT Information System using C++.

The system was developed as a console-based prototype demonstrating the main functions of the Student and Lecturer modules.

2. Programming Language

The system was developed using:

- C++
- Embarcadero Dev-C++

3. Student Functions

The student module provides the following functions:

- Student login
- Unit registration
- Viewing registered units
- Viewing marks
- Accessing the LMS
- Viewing notes
- Viewing assignments
- Viewing CATs

4. Lecturer Functions

The lecturer module provides:

- Lecturer login
- Viewing assigned units
- Uploading notes
- Creating assignments
- Creating CATs
- Entering student marks

5. Marks Processing

The system accepts:

- Assignment marks out of 20
- CAT marks out of 20
- Examination marks out of 60

The total mark is calculated by adding the three components.

The system then assigns a grade based on the total mark.

6. Unit Registration and LMS Synchronization

When a student registers a unit through the Student Portal, the unit is stored in the student's registered units.

The registered unit can then be accessed through the LMS.

 7. Marks Synchronization

When a lecturer enters marks through the LMS, the marks are stored in the system.

The student can then view the marks through the Student Portal.

8. Login System

The system provides separate login functions for students and lecturers.

Users must provide a valid ID and password before accessing their respective modules.

9. Data Structures

The program uses structures to store information about:

- Students
- Lecturers
- Units
- Marks

Vectors are used to store multiple records during program execution.

10. Testing

The system was tested by performing different operations including:

- Student login
- Lecturer login
- Unit registration
- Viewing registered units
- Entering marks
- Viewing marks
- Accessing the LMS
- Logging out

11. Current Limitations

The current version is a prototype. Data is stored temporarily while the program is running and is lost when the program closes.

Some LMS functions such as uploading actual files and creating real assignments are represented as prototype functions.

 12. Conclusion

The programming phase implements the main requirements of the proposed JKUAT Information System. The C++ prototype demonstrates student and lecturer interaction, unit registration, LMS access and the flow of academic marks between the LMS and Student Portal.
