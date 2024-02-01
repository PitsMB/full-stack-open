```mermaid
sequenceDiagram
    participant Browser
    participant Server
    Browser->>Server: GET https://studies.cs.helsinki.fi/exampleapp/notes
    Server->>Browser: Content-Type: text/html
    Browser->>Server: GET https://studies.cs.helsinki.fi/exampleapp/main.css
    Server->>Browser: Content-Type: text/css
    Browser->>Server: GET https://studies.cs.helsinki.fi/exampleapp/main.js
    Server->>Browser: Content-Type: application/javascript
    Browser->>Server: GET https://studies.cs.helsinki.fi/exampleapp/data.json
    Server->>Browser: Content-Type: application/json
    Browserr->>Server: POST https://studies.cs.helsinki.fi/exampleapp/new_note
    Server->>Browser: Content-Type: text/html
    Browser->>Server: GET https://studies.cs.helsinki.fi/exampleapp/notes
    Server->>Browser: Content-Type: text/html
    Browser->>Server: GET https://studies.cs.helsinki.fi/exampleapp/main.css
    Server->>Browser: Content-Type: text/css
    Browser->>Server: GET https://studies.cs.helsinki.fi/exampleapp/main.js
    Server->>Browser: Content-Type: application/javascript
    Browser->>Server: GET https://studies.cs.helsinki.fi/exampleapp/data.json
    Server->>Browser: Content-Type: application/json
```