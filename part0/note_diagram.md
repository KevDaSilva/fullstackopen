```mermaid
    sequenceDiagram

    actor u as user
    participant b as browser
    participant s as server

    u->>b: Enter note text
    u->>b: Click "Save" button
    b->>s: POST https://studies.cs.helsinki.fi/exampleapp/new_note
```
