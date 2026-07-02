# UMaT Management System

Python inheritance LAB Assignment for EL 162/23.

## What It Contains

Models people at UMaT using a parent class (`Person`) and two child classes (`Student` and `Lecturer`).

## Classes

- **Person** — has `name`, `age`, and `display_info()`
- **Student** — inherits from Person, adds `student_id` and `enroll_course()`
- **Lecturer** — inherits from Person, adds `employee_id` and `teach_course()`



## Output

```
--- Student ---
Name: Kwame, Age: 20
Student ID: S12345
Kwame enrolled in OOP

--- Lecturer ---
Name: Dr. Cobbinah, Age: 45
Employee ID: E98765
Dr. Cobbinah is teaching OOP
```

## Key Features

- `super()` used to call parent constructor and methods
- `display_info()` overridden in both child classes
- Shows single inheritance, method overriding, and code reuse
