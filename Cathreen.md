```mermaid
graph TD
    A[Data Input Phase] --> B[Clock-In/Out Data]
    A --> C[Screenshots]
    A --> D[Presentation Data]
    A --> E[Focus Tracking Data]
 
    B --> F[Processing Phase]
    C --> F
    D --> F
    E --> F
 
    F --> G[Focus Score]
    F --> H[Professionalism Score]
    F --> I[Curiosity Score]
    F --> J[Performance Score]
    F --> K[Impact Score]
 
    G --> L[Review & Score Generation Phase]
    H --> L
    I --> L
    J --> L
    K --> L
 
    L --> M[Detailed Review]
    L --> N[Personalized Suggestions]
 
    M --> O[Focus Improvement Suggestions]
    M --> P[Professionalism Improvement Suggestions]
    M --> Q[Curiosity Improvement Suggestions]
    M --> R[Performance Improvement Suggestions]
    M --> S[Impact Improvement Suggestions]
 
    N --> T[Mentorship Phase]
    T --> U[Mentor in Presentations]
    T --> V[Focus In/Focus Out Assistance]
