# Academic Organization Ontology

## Overview

This project presents an Academic Organization Ontology developed using OWL 2.0 in the Protégé environment. The ontology models the structure and semantic relationships of an academic institution, including students, professors, departments, courses, classrooms, examinations, academic programs, semesters, libraries, and staff.

The ontology was developed as part of the Knowledge Representation course at the University of Verona. Logical consistency was verified using the HermiT Reasoner, and several DL Queries were executed to retrieve knowledge from the ontology.

---

## Objectives

- Design an academic ontology using OWL 2.0.
- Represent academic knowledge in a semantic structure.
- Model students, professors, departments, and courses.
- Define object properties and data properties.
- Create individuals representing real academic entities.
- Verify ontology consistency using HermiT Reasoner.
- Execute DL Queries for knowledge retrieval.
- Publish the complete project on GitHub.

---

## Ontology Statistics

| Component | Count |
|-----------|------:|
| Classes | 30+ |
| Object Properties | 30+ |
| Data Properties | 20+ |
| Individuals | 30+ |
| Reasoner | HermiT |
| Ontology Language | OWL 2.0 |

---

## Main Classes

- AcademicOrganization
- AcademicProgram
- Person
  - Student
  - Professor
  - Staff
- Department
- Course
- Classroom
- Semester
- Examination
- Library

---

## Object Properties

Examples include:

- enrollsIn
- teaches
- belongsToDepartment
- studiesIn
- supervises
- attendsClass
- offersCourse
- registersFor
- hasAdvisor
- evaluates
- conductedIn
- assignedTo

---

## Data Properties

Examples include:

- studentName
- studentID
- professorName
- courseCode
- departmentName
- semesterName
- credits
- classroomNumber
- examDate
- emailAddress
- phoneNumber

---

## Reasoning

The ontology was successfully verified using the **HermiT Reasoner**. The reasoning process confirmed that the ontology is logically consistent and free from semantic conflicts.

---

## DL Queries

Example DL Queries:

```
:Student
```

```
:Professor
```

```
:Course
```

```
:Department
```

```
Student and enrollsIn some Course
```

```
Professor and teaches some Course
```

```
Course and offeredBy some Department
```

---

## Tools Used

- Protégé 5.x
- OWL 2.0
- HermiT Reasoner
- GitHub

---

## Repository Contents

- AcademicOrganizationOntology.owl
- Project_Report.pdf
- README.md

---

## Author

Mahamuda Akter

Registration No.: VR546532

Department of Computer Science

University of Verona

---

## Course

Knowledge Representation

University of Verona
