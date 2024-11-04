
```mermaid
flowchart 
    node1["Animation Breakdown"]
    node2["Motion Capture [X-Sense]"]
    node3["Cleanup & Expressions [iClone]"]
    node4["Lip-sync [Audio2Face]"]
    node5["Shot Integration [Unreal]"]
    node6["Client Review"]

    node1 --> node2
    node2 --> node3
    node3 --> node4
    node4 -- Creative Director Review --> node5
    node5 -- Creative Director Review --> node6

```