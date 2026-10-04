# Use Case Diagram

## Online Loan Application System

```mermaid
flowchart LR
    Customer --> System[Online Loan Application System]
    LoanOfficer[Loan Officer] --> System
    CreditAnalyst[Credit Analyst] --> System

    Customer --> A[Start Application]
    Customer --> B[Enter Personal Information]
    Customer --> C[Upload Documents]
    Customer --> D[Submit Application]
    Customer --> E[Track Application]
    Customer --> F[Receive Notifications]

    LoanOfficer --> G[Review Application]
    LoanOfficer --> H[Request Additional Information]

    CreditAnalyst --> I[Assess Application]
    CreditAnalyst --> J[Record Decision]
