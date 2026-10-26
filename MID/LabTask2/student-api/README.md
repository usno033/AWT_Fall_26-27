
A NestJS REST API for managing a university's departments, students and courses, using TypeORM and PostgreSQL. All data is stored in a real database, and the tables are created using database migrations.

**Student Details :**
SL No : 08 ; Name : USNO KARMAKAR ; ID : 23-51033-1 ; Sec: D

**Project Structure :**
```
src/
├── database/
│   └── migrations/
└── modules/
    ├── department/
    │   ├── dto/
    │   ├── entities/
    │   ├── department.controller.ts
    │   ├── department.service.ts
    │   └── department.module.ts
    ├── student/
    │   ├── dto/
    │   ├── entities/
    │   ├── student.controller.ts
    │   ├── student.service.ts
    │   └── student.module.ts
    └── course/
        ├── dto/
        ├── entities/
        ├── course.controller.ts
        ├── course.service.ts
        └── course.module.ts
```

**Entities :**

| Entity | Fields |
| Department | id, name, code, description |
| Student | id, firstName, lastName, email, phone, dateOfBirth, departmentId, createdAt |
| Course | id, title, code, credits, description, departmentId |


