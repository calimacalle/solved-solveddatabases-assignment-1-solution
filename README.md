Download Link: https://assignmentchef.com/product/solved-solveddatabases-assignment-1-solution
<br>
ScopePreparation of this assignment requires implementation of the conceptual modeling tasks included in laboratory 1 and implementation of the experiments included in laboratory of week 2.ObjectivesThe objective of this assignment is:• to design a conceptual database schema (OMT diagram) from a given specification of database domain.• to retranslate a conceptual schema into a collection of relational schemas.

Task 1 Design and diagrams (3 marks)

Read the description of a sample database domain given below.Consider the following information about a university database:Every faculty staff has a staff number, a name, date of birth, level of position, work in department.Each project has a project number, a sponsor name (e.g., ARC, URC), a starting date, an ending date, and a budget.Each student has a student number, a name, date of birth, and a degree program (e.g., BCs, or MCs or PhD).Each project is managed by one faculty staff.Each project is worked by one or more faculty staffs.Staffs can work on multiple projects.Each project is worked on by one or more students (as the project’s researchassistants).When students work on a project, a staff must supervise their work on the project.Students can work on multiple projects, in which case they will have a supervisor for each one.Departments have department name, a main office, header of the department.Faculty staffs work in one or more departments, and for each department that they work in, a time percentage is associated with their job.Students have one major department in which they are working on their degree.It is forbidden to add any additional attributes to the specification given above.

Use a notation of simplified OMT classes explained to you during the lecture classes to design a conceptual schema of a database domain described above. Apply a conceptual modelling methodology explained to you in a presentation Conceptual modelling.You have “read through” the specification given above several times and in the first “pass” identify the classes of objects, in the second “pass” identify associations and association classes, in the third “pass” identify attributes and link attributes, in the fourth “pass” find identifiers, in the fifth pass find qualifications of associations and finally, in the last “pass” find the generalization hierarchies (see presentation 3 Conceptual modelling, slide 3).

Task 2 Implementation of conceptual schema (1 mark)

Implement the conceptual schema obtained in the previous step using collection of relational schemas, i.e. a script with SQL statements CREATE TABLE and ALTERTABLE. Execute the script.DeliverablesSubmit an archive file assignment1.zip contains the following two tasks’ files onMoodle.

Task 1

A soft copy of the design process and OMT diagrams in a PDF file task1.pdf.A complete soft copy of description of design process together with a drawing of aconceptual schema in a notation of simplified OMT classes must be shown. You can find a sample format of a description in the solutions of example.Note that delivery of a conceptual schema without a complete description of thedesign process will result in no marks being awarded for the assessment task!A diagram of conceptual schema must be consistent with a graphical notationexplained to you during the lecture classes. No other notation will be accepted. Any electronic drawing tools are acceptable.

Task2A soft copy of a text file task2.txt contains execution of the relational schemas (SQL statement scripts and feedbacks).Before execute the SQL scripts, you must run sqlplus, then use the following statements to generate output results into a text file.SET ECHO ONSPOOL task2.txt@your-scripts-file-nameSPOOL OFF

Note that delivery of relational schemas without execution will result in no marksbeing awarded for the assignment task!