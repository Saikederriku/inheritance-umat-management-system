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
Name: KENNETH DAVID KORLEY KISSEIH , Age: 18
Student ID: FOE.41.006.097.25
KENNETH DAVID KORLEY KISSEIH enrolled in Object Oriented Programming

--- Lecturer ---
Name: Dr. Cobbinah Matthew, Age: 45
Employee ID: I DON'T KNOW
Dr. Cobbinah Matthew is teaching Object Oriented Programming
```

## Key Features

- `super()` used to call parent constructor and methods
- `display_info()` overridden in both child classes
- Shows single inheritance, method overriding, and code reuse
