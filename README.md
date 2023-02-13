# markdown-example

Here is a sample flowchart of the process:

```mermaid
flowchart TD;
    A[0. Get Started] --> B[1. Choose a Setup];
    B -- MC Setup --> C[2a. Purchase Hardware];
    B -- CC Setup --> D[2b. Purchase Hardware];
    C -- I want something easy to use --> E[3a. Arduino Leonardo Setup]
    C -- I want something cheap --> F[3b. Pro Micro Setup]
    C -- I would be changing programs a lot --> G[3c. Teensy 2.0 Setup]
    D -- I want something easy to use --> H[3d. Arduino Leonardo Setup]
    D -- I want something cheap --> I[3e. Pro Micro Setup]
    D -- I would be changing programs a lot --> J[3f. Teensy 2.0 Setup]
    E --> K[4a. Flash your first program]
    F --> K
    G --> K
    H --> L[4b. Hardware setup]
    I --> L
    J --> L
    L --> M[5b. Flash PABotBase]
    K --> N[5a. Generate and run programs]
    M --> O[6. Software Setup]
    O --> P[7. Running CC Programs]
    N -- I am ready to move on to CC -.-> Q[x. Getting Additional Hardware]
    Q -.-> L
```
