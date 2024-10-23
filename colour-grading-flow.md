```mermaid
flowchart TD
    A[Premiere Media] --Only when moving to Colour for the first time--> B[Backup]
    B --> C[Davinci Resolve Media]
    C --> D[Resolve Exports]
    D --Harvest from individual export folders--> A
    C --"If things go Pete Tong"--> A

    E[New Media] --> C
    
```