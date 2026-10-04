# To-Be Process

## Improved Online Loan Application Process

```mermaid
flowchart TD
    A[Start] --> B[Customer starts online application]
    B --> C[Enter personal information]
    C --> D[Upload documents]
    D --> E[Validate application]
    E --> F{Information complete?}
    F -->|No| G[Show missing information]
    G --> C
    F -->|Yes| H[Submit application]
    H --> I[Loan Officer reviews application]
    I --> J{Additional information needed?}
    J -->|Yes| K[Request additional information]
    K --> L[Customer provides information]
    L --> I
    J -->|No| M[Credit Analyst assesses application]
    M --> N[Record lending decision]
    N --> O[Notify customer]
    O --> P[End]
