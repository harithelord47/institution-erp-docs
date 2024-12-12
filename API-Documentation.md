# API Documentation

## Endpoints

### 1. **POST /users**
- **Description**: Create a new user.
- **Request Body**: 
```json
{
  "name": "John Doe",
  "email": "john.doe@example.com",
  "role": "faculty"
}
```

- **Response**:
```json
{
  "id": 1,
  "name": "John Doe",
  "email": "john.doe@example.com",
  "role": "faculty"
}
```

### 2. **GET /courses**
- **Description**: Fetch all courses.
- **Response**: 
```json
[
  {
    "id": 1,
    "course_name": "Computer Science 101",
    "course_code": "CS101",
    "faculty": "Dr. Smith"
  },
  {
    "id": 2,
    "course_name": "Mathematics 101",
    "course_code": "MATH101",
    "faculty": "Dr. Johnson"
  }
]
```

### **Authentication**
- **Bearer Token**: Use a JWT token in the header for authentication.
- **Example**: Authorization: Bearer <token>