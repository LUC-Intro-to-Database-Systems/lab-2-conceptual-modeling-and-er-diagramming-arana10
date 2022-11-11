<img width="788" alt="Screen Shot 2022-11-11 at 11 52 18 AM" src="https://user-images.githubusercontent.com/97986841/201399985-3d44739f-c713-4b41-9812-2f96b70aa620.png">

 #DESCRIPTION 

- **STUDENT**: A student is associated with a seat and course. A student can consist of StudentID, student name, student address. 

- **SEAT**: A seat is associated with a student. A seat consists of seat no and seat position. 

- **COURSE**: A course is associated with a student and a section. A course consists of course_name and course_number.

- **SECTION**: A section is associated with a course and a professor. A section consists of section_number. 

- **PROFESSOR**: A professor is associated with section. A professor can consist of ProfessorID, professor name, and professor faculty.

- **INSTRUCTOR**: An instructor is associated with a course. An instructor can consist of InstructorNo, instructor name, and instructor faculty.  

#RELATIONSHIP: 

- A **STUDENT** can <ins>fill</ins> one and only one **SEAT**, each **SEAT** can be <ins>filled</ins> by one and only one **STUDENT**. 

- A **STUDENT** can <ins>take</ins> one or more **COURSE**, each **COURSE** can be <ins>taken</ins> by one or more **STUDENT**.

- A **COURSE** <ins>has</ins> one or more **SECTION**, each **SECTION** <ins>has</ins> one or more **COURSE**.

- A **PROFESSOR** can <ins>teach</ins> zero or more **SECTION**, each **SECTION** can be <ins>taught</ins> be one **PROFESSOR**. 

- An **INSTRUCTOR** can <ins>teach</ins> one or more **COURSE**, each **COURSE** can be <ins>taught</ins> by one **INSTRUCTOR**. 

#ASSUMPTIONS:
- Can a **STUDENT** have more than one **SEAT**? No

- Can a **COURSE** exist with zero **STUDENTS**? No

- Can a **PROFESSOR** teach zero **COURSES**?  No
