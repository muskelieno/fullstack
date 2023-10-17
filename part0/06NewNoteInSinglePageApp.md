# exercise 0.6 New note in single page app diagram

```mermaid

sequenceDiagram
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    Note right of browser: The browser cretes a new note, redraws the page and sends the note to server as json payload

```
