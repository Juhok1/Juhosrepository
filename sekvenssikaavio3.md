``` mermaid

    sequenceDiagram
        participant browser
        participant server
    
        browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
        activate server
        server-->>browser: created
        deactivate server
        Note: the browser already have JavaScript code for dealing new data and sendig it to server
```
