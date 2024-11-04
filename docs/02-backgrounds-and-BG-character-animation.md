

```mermaid
flowchart TD
    node1["Proprietary GPT"]
    node2["DALL·E Image Gen"]
    node2a["In-Paint adjustments"]
    node4["Stable Diffusion Face Refinement"]
    node5["Stable Diffusion Upscale"]
    node6["Runway.ml Video Gen"]
    node7["Photoshop Layer Separation"]
    node8["Unreal Composite"]
    node9["Final Review"]

    node1 --> node2
    node2 --> node2a
    node2a --> node4
    node4 --> node5
    node5 --> node6
    node2a ---> node6
    node6 --> node7
    node7 --> node8
    node8 --> node9

```
Original image generation 
![image](https://github.com/user-attachments/assets/863ef60d-6b9f-4a4f-aff3-fbd819fdf1ce)

Issues with image
![image-1](https://github.com/user-attachments/assets/43dad8fc-7a88-4b27-ba64-02d695dadd5e)


ComfyUI Upscale and Facefix Workflow
![image-2](https://github.com/user-attachments/assets/4bba2659-e678-4fbd-bf21-f103c88be3ab)

Output of ComfyUI Workflow 
![image-3](https://github.com/user-attachments/assets/3fa6da8a-283f-475a-b876-7f6e3d06dc1a)


Photoshop Beta Character removal (to give space for 3d character integration) 

***This process can be replaced with Dali-Inpainting***
![image-5](https://github.com/user-attachments/assets/b566ff70-4ba6-45c6-835a-8e9ff2979fa6)

