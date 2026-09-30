# Use Case Diagram

## Student Registration System

```mermaid
flowchart LR
    Student((Student))
    Advisor((Academic Advisor))
    Admin((University Admin))

    System[Student Registration System]

    Student -->|View modules| System
    Student -->|Check prerequisites| System
    Student -->|Select modules| System
    Student -->|Check timetable| System
    Student -->|Submit registration| System
    Student -->|Receive confirmation| System

    Advisor -->|Review student registration| System
    Advisor -->|Provide guidance| System

    Admin -->|Manage modules| System
    Admin -->|Manage registration rules| System
    Admin -->|Generate reports| System
