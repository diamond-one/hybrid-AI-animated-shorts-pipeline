

```mermaid
flowchart TD
    node1["Proprietary GPT"]
    node2["[Dali] Image Generation"]
    node2a["[Photoshop] Focal Character Removal"]
    node4["[Stable Defusion] Custom Face Detail Refinement pass"]
    node5["[Stable Defusion] Custom Image Upscale in ComfyUI"]
    node6["[Runway.ml] IMG->VIDEO Generation"]
    node7["[Photoshop] Layer Separation"]
    node8["Unreal Engine Composite"]
    node9["Final Review"]

    node1 --> node2
    node2 -- GPT/Image Iteration--> node1
    node2 --> node4
    node4 --> node5
    node5 --> node2a
    node2a--Remove the need for photoshop by building lama object removal workflow--> node6
    node6 --IMG-VIDEO Iteration --> node7
    node7 --> node8
    node8 --> node9

```
Original image generation 
![Initial Image Generated](image.png)

Issues with image

![Issues with image](image-1.png)

ComfyUI Upscale and Facefix Workflow
![comfyUI workflow](image-2.png)

Output of ComfyUI Workflow 
![comfyUI OUTPUT](image-3.png)

Photoshop Beta Character removal (to give space for 3d character integration)
![alt text](image-5.png)
