# Database Schema

## Entities and Relationships
- **Users**: Stores user information (admins, faculty, students).
- **Courses**: Stores information about academic courses.
- **Events**: Stores event data for workshops, seminars, etc.
- **Certificates**: Stores certificates related to events and courses.
- **Marks**: Stores student performance data.

## ER Diagram
![ER Diagram](path/to/er-diagram.png)

## Sample Data
- **Users Table**: `id, name, email, role, created_at`
- **Courses Table**: `id, course_name, course_code, faculty_id`
- **Certificates Table**: `id, certificate_name, user_id, event_id, date_uploaded`

