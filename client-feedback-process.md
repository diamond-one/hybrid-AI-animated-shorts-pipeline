
# Client Feedback Process

This process highlights how client feedback is managed throughout the production stages.

```mermaid
flowchart TD
    node1["Initial Character Mock-up"]
    node1a["Model Sheets Created"]
    node2["Client Review/Direction"]
    node3["Character Creation (CC4)"]
    node4["Internal Review"]
    node5["Update Character(?)"]
    node5a["Model Sheets Created"]
    node6["Submit to Client"]
    node7{"Client Approval?"}
    node8["Next Stage"]

    node1 --> node1a --> node2
    node2 --> node3
    node3 --> node4
    node4 --> node5
    node5 --> node5a  --> node6
    node6 --> node7
    node7 -- Yes --> node8
    node7 -- No --> node5

    classDef note fill:#ccc,stroke:#000,stroke-width:2px,color:#000;
    class node2,node6 note;


```
