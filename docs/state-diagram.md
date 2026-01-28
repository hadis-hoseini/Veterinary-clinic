```mermaid
stateDiagram
    [*] --> Requested
    Requested --> Approved
    Requested --> Rejected
    Approved --> Completed
    Approved --> Cancelled
```
