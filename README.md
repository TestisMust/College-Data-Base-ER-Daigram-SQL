A comprehensive database system designed to efficiently manage student records, courses, and faculty details in a college setting. The system ensures seamless integration and management of academic data across various departments.

**Project Highlights:**

🔍 Database Creation with ER Diagram:

**Entities and Attributes:**

Students: Attributes include StudentID, FirstName, LastName, DOB, Gender, DepartmentID, and EnrollmentDate.
Departments: Attributes include DepartmentID, DepartmentName, and DepartmentHead.
Courses: Attributes include CourseID, CourseName, Credits, DepartmentID, and InstructorID.
Instructors: Attributes include InstructorID, FirstName, LastName, Title, HireDate, and DepartmentID.
Enrollments: Attributes include EnrollmentID, StudentID, CourseID, EnrollmentDate, and Grade.
Designing the Database Schema:

Created a detailed ER diagram to map out the relationships and attributes of each entity.

**Establishing Relationships:**

One-to-Many relationship between Departments and Students (one department can have multiple students).
One-to-Many relationship between Departments and Courses (one department can offer multiple courses).
One-to-Many relationship between Instructors and Courses (one instructor can teach multiple courses).
Many-to-Many relationship between Students and Courses, managed through the Enrollments table.

**Key Features:**

Efficient tracking of student enrollments and course assignments.
Clear relationships between academic departments, courses, and instructors.
Streamlined data management for a complex academic environment.

**This project was an incredible learning experience, and I'm excited to leverage these skills in future projects.
**
