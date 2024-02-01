```mermaid
graph TD;
    Base url = "https://studies.cs.helsinki.fi/exampleapp";
    Client-->'GET/notes';
    'text/html'<--Server;
    Client-->'GET/main.css';
    'text/css'<--Server;
    Client-->'GET/main.js';
    'application/javascript'<--Server;
    Client-->'GET/data.json';
    'application/json'<--Server;
```