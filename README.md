# Academic Organization Ontology

A comprehensive Academic Organization Ontology developed using OWL 2.0 in Protégé for semantic knowledge representation of a university environment.

---

## Overview

This project models the structure and activities of an academic institution using Semantic Web technologies. The ontology represents students, professors, departments, faculties, courses, examinations, classrooms, research centers, libraries, and many other university entities.

The ontology has been developed in Protégé using OWL 2.0 and verified with the HermiT Reasoner to ensure logical consistency.

---

## Objectives

- Model an academic organization using ontology concepts.
- Represent university entities and their relationships.
- Demonstrate semantic reasoning using HermiT.
- Execute DL Queries for knowledge retrieval.
- Apply Semantic Web technologies in higher education.

---

# Ontology Structure

The ontology includes the following major concepts:

- Academic Organization
- Faculty
- Department
- Academic Program
- Course
- Semester
- Classroom
- Laboratory
- Library
- Research Center
- Student
- Professor
- Lecturer
- Teaching Assistant
- Administrative Staff
- Dean
- Registrar
- Vice Chancellor
- Examination
- Assignment
- Attendance
- Result
- Scholarship
- Graduation
- Certificate
- Event
- Transport
- Hostel

and many additional supporting classes.

---

# Ontology Statistics

| Component | Count |
|-----------|------:|
| Classes | 56 |
| Object Properties | 45 |
| Data Properties | 41 |
| Individuals | 82 |
| Axioms | 854 |

---

# Object Properties

Examples include:

- enrolledIn
- teaches
- belongsToDepartment
- belongsToFaculty
- hasAdvisor
- hasAssignment
- hasAttendance
- hasResult
- conductsExam
- worksIn
- managesDepartment
- supervisesStudent
- issuesCertificate
- organizesEvent
- participatesIn
- providesScholarship
- usesLibrary
- usesLaboratory
- assignedToClassroom
- offersCourse

and many others.

---

# Data Properties

Examples include:

- studentID
- employeeID
- teacherID
- fullName
- email
- phoneNumber
- age
- gender
- CGPA
- credits
- courseCode
- courseTitle
- examDate
- examTime
- assignmentMarks
- attendancePercentage
- roomNumber
- joiningDate
- salary
- certificateNumber

and many more.

---

# Individuals

The ontology contains multiple instances representing real university entities, including:

- Students
- Professors
- Departments
- Faculties
- Courses
- Laboratories
- Libraries
- Classrooms
- Research Centers
- Administrative Staff

---

# Reasoning

The ontology has been verified using the **HermiT Reasoner**.

Reasoning validates:

- Class hierarchy
- Object property hierarchy
- Data property hierarchy
- Class assertions
- Object property assertions
- Individual consistency

---

# Example DL Queries

```
Student
```

```
Professor
```

```
Course
```

```
Department
```

```
Student and (enrolledIn some Course)
```

```
Professor and (teaches some Course)
```

```
Department and (offersCourse some Course)
```

```
Student and (hasAdvisor some Professor)
```

---

# Software Used

- Protégé 5.x
- OWL 2.0
- HermiT Reasoner
- GitHub

---

# Repository Contents

```
AcademicOrganizationOntology.owl
README.md
Project_Report.pdf
```

---

# Author

Mahamuda Akter

Student ID: VR546532

University of Verona
