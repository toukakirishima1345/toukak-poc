```mermaid
graph LR
    A[Click Me] --> B{XSS};
    style A fill:#f9f,stroke:#333,stroke-width:2px
    click A "javascript:alert(document.baseURI)" "XSS Link";
```
