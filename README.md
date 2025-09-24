# Campus-Course-Records-Manager-CCRM-
A console-based Java application called Campus Course &amp; Records Manager (CCRM) that lets an institute manage Student , Courses ,  Grades &amp; Transcripts and File Utilities.
# Campus Course & Records Manager (CCRM)

A comprehensive Java application for managing campus courses, student records, enrollments, and grades.

## Features

- Student Management with Builder Pattern
- Course Management with Enrollment System
- Grade Calculation and GPA Tracking
- File Operations and Backup System
- Comprehensive Reporting

## Technologies Used

- Java 11+
- Object-Oriented Programming Principles
- Design Patterns (Singleton, Builder)
- File I/O Operations
- Stream API and Lambda Expressions

## Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/campus-course-records-manager.git

# Navigate to project directory
cd campus-course-records-manager

# Compile the application
javac -d bin src/main/java/edu/ccrm/CCRM.java

# Run the application
java -cp bin edu.ccrm.CCRM
```

## Project Structure

```
src/
└── main/
    └── java/
        └── edu/
            └── ccrm/
                ├── CCRM.java                 # Main application class
                ├── config/                   # Configuration classes
                ├── domain/                   # Entity classes (Student, Course, etc.)
                ├── service/                  # Business logic services
                ├── util/                     # Utility classes
                ├── io/                       # File operations
                └── exception/                # Custom exceptions
```

## Code Example

```java
// Create a student using Builder pattern
Student student = new Student.StudentBuilder()
    .id("S101")
    .regNo("REG101")
    .fullName("Jane Doe")
    .email("jane@example.com")
    .status(Student.Status.ACTIVE)
    .build();
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
