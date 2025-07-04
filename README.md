# api-students
API to "Golang do Zero" course students

Routes:
- GET /students - List all students
- POST /students - Create student
- GET /students/:id - Get informations from a specific student
- PUT /students/:id - Update students
- DELETE /Students/:id - Delete student

Student struct:
- Name (string)
- CPF (int)
- Email (String)
- Age (int)
- Active (bool)