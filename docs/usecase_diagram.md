# Use Case Diagram (Mermaid)

```mermaid
flowchart TD

    %% Actors
    PM([👤 Project Manager])
    TM([👤 Team Member])

    %% Use Cases
    UC1((Create Task))
    UC2((View Tasks))
    UC3((Update Task Status))
    UC4((Determine Status))
    UC5((View Performance Report))

    %% Connections
    PM --> UC1
    PM --> UC4
    PM --> UC5

    TM --> UC2
    TM --> UC3

