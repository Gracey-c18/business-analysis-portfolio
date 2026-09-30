# To-Be Process

## Improved Student Registration Process

```mermaid
flowchart TD
    A[Start] --> B[Student logs in]
    B --> C[View available modules]
    C --> D[Select module]
    D --> E[Check prerequisites]
    E --> F{Prerequisites met?}
    F -->|No| G[Show error message]
    G --> D
    F -->|Yes| H[Check timetable clash]
    H --> I{Timetable clash?}
    I -->|Yes| J[Show clash warning]
    J --> D
    I -->|No| K[Review registration]
    K --> L[Submit registration]
    L --> M[Registration confirmed]
    M --> N[End]
