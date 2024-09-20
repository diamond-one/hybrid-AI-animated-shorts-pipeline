
# Project Gantt Chart

This Gantt chart shows the timeline for the entire project, highlighting key stages such as character creation, asset development, and final integration.

```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title Project Timeline
    section Initial Design
    Character Design (CC4) :a1, 2024-09-20, 14d
    section Client Review
    Client Review #1 :a2, after a1, 3d
    section Modifications
    Modifications :a3, after a2, 7d
    section Final Review
    Client Review #2 :a4, after a3, 3d
    section Integration
    Export to UE5 :a5, after a4, 5d
```
