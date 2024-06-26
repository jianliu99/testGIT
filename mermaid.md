# Sequence Diagram for Service Calls

Below is a sequence diagram showing how the Account Service and CIE Service both call the Auth Service.

```mermaid
sequenceDiagram
    participant Account as Account Service
    participant Auth as Auth Service
    participant CIE as CIE Service

    Account->>Auth: Call Auth Service
    CIE->>Auth: Call Auth Service
