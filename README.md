# holbertonschool-web_react

This repository contains TypeScript exercises for the Holberton School web React curriculum.

## TypeScript

### Task 0: Creating an interface for a student

Created a `Student` interface with typed student fields, added two student objects, stored them in `studentsList`, and rendered a table in the DOM with each student's first name and location.

### Task 1: Let's build a Teacher interface

Created a `Teacher` interface with readonly `firstName` and `lastName`, optional `yearsOfExperience`, required employee fields, and an index signature for extra properties such as `contract`.

### Task 2: Extending the Teacher class

Added a `Directors` interface extending `Teacher` with a required `numberOfReports` property.

### Task 3: Printing teachers

Created a `printTeacherFunction` interface and implemented `printTeacher`, which formats a teacher name as the first initial plus full last name.

### Task 4: Writing a class

Created `StudentClass` with constructor interfaces and class interfaces. The class stores a student's name, returns the first name with `displayName`, and returns `Currently working` with `workOnHomework`.

### Task 5: Advanced types Part 1

Created `DirectorInterface` and `TeacherInterface`, implemented `Director` and `Teacher` classes, and added `createEmployee` to return a teacher or director depending on salary type and value.

### Task 6: Creating functions specific to employees

Added `isDirector` as a type predicate and `executeWork` to call director-specific or teacher-specific work methods based on the employee type.

### Task 7: String literal types

Created a `Subjects` string literal type allowing only `Math` or `History`, and implemented `teachClass` to return the correct teaching message.

### Task 8: Ambient Namespaces

Created row types in `interface.ts`, added the provided `crud.js` library, declared its ambient TypeScript types in `crud.d.ts`, and used the CRUD functions from `main.ts`.

### Task 9: Namespace & Declaration merging

Created the `Subjects` namespace with `Teacher`, `Subject`, `Cpp`, `React`, and `Java`. Used declaration merging to add subject-specific teaching experience fields to `Teacher`.

### Task 10: Brand convention & Nominal typing

Created branded `MajorCredits` and `MinorCredits` interfaces and implemented functions to sum credits while preserving their nominal types.
