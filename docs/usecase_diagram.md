flowchart TD

    %% Actors
    PetOwner([🐾 Pet Owner])
    Vet([🩺 Veterinarian])
    Admin([👤 Admin])

    %% Use Cases styled as ellipse (GitHub-friendly)
    UC1([Register Pet])
    UC2([Book Appointment])
    UC3([Request Treatment])
    UC4([View Medical History])
    UC5([Approve Requests])
    UC6([Manage Payments])
    UC7([Manage Pets])
    UC8([Manage Vets & Schedules])

    %% Connections
    PetOwner --> UC1
    PetOwner --> UC2
    PetOwner --> UC3
    PetOwner --> UC4

    Vet --> UC2
    Vet --> UC5

    Admin --> UC7
    Admin --> UC8
    Admin --> UC6

    %% Blue oval style (works in GitHub)
    style UC1 fill:#87CEFA,stroke:#333,stroke-width:2px
    style UC2 fill:#87CEFA,stroke:#333,stroke-width:2px
    style UC3 fill:#87CEFA,stroke:#333,stroke-width:2px
    style UC4 fill:#87CEFA,stroke:#333,stroke-width:2px
    style UC5 fill:#87CEFA,stroke:#333,stroke-width:2px
    style UC6 fill:#87CEFA,stroke:#333,stroke-width:2px
    style UC7 fill:#87CEFA,stroke:#333,stroke-width:2px
    style UC8 fill:#87CEFA,stroke:#333,stroke-width:2px
