Here is a simple flow chart:

```mermaid
graph TD;
    browser-->server : Get HTML;
    
    server-->browser: HTML document;
    
    browser-->server: Post new note;
    server-->browser: Get notes
```
