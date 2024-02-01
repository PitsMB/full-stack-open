```mermaid
graph TD;
    Client-->'GET https://studies.cs.helsinki.fi/exampleapp/notes';
    'ContentType: text/html'<--Server;
    Client-->'GET https://studies.cs.helsinki.fi/exampleapp/main.css';
    'ContentType: text/css'<--Server;
    Client-->'GET https://studies.cs.helsinki.fi/exampleapp/main.js';
    'ContentType: application/javascript'<--Server;
    Client-->'GET https://studies.cs.helsinki.fi/exampleapp/data.json';
    'ContentType: application/json'<--Server;
```