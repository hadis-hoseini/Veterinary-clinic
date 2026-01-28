```mermaid
flowchart TD
    Start([Start])
    A[Select Pet]
    B[Select Service]
    C[Select Date & Time]
    D{Time Slot Available?}
    E[Confirm Appointment]
    F[Show Error Message]
    End([End])

    Start --> A --> B --> C --> D
    D -- Yes --> E --> End
    D -- No --> F --> End
