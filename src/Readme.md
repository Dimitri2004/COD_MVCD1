```mermaid
sequenceDiagram 
    participant User
    participant WebApp
    participant API
    participant Database

    User->>WebApp: Request to view data
    WebApp->>API: Fetch data from API
    API->>Database: Query for data
    Database-->>API: Return data
    API-->>WebApp: Send data to web app
    WebApp-->>User: Display data
```
