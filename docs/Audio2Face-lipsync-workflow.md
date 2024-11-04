
```mermaid
flowchart TD
    node1["Character Animation [Body/Expression] in iClone"]
    node2["Automatic Lipsync"]
    node3["Export for Unreal"]
    node4["Integrate Character in Unreal"]
    node5["Export from UE"]
    node6["Final edit in Premiere"]
    node7["Director/Client Review"]

    node1 --> node2
    node2 --Director Review--> node3
    node3 --> node4
    node4 --> node5
    node5 --Director Review --> node6 
    node6 --> node7
    
    style node7 fill:#808080,stroke:#000000,color:#ffffff

```

Free alternatives which need development:
LivePortrait with Face fix and upscale in Stable Diffusion 
wave-to-face with face fixes and upscale in Stable Diffusion 


Gen AI is like throwing the dice, we are constantly working on ways to improve out pipeline so our results are less random and directable 