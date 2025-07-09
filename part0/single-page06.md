```mermaid
sequenceDiagram
participant browser
participant server
browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/spa
    activate server
server-->>{"message":"note created"}

    deactivate server
```
