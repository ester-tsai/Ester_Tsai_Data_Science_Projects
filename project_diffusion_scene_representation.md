## Diffusion Model Scene Representation 

[Research Project Proposal](/pdf/Diffusion Scene Representation Project Proposal.pdf)

### Project Overview

Elevator Pitch: [![Elevator Pitch](https://img.youtube.com/vi/V5Za7lvA5lE/0.jpg)](https://www.youtube.com/watch?v=V5Za7lvA5lE)

The ability of latent diffusion models (LDMs) to generate realistic images from textual descriptions has seen remarkable advancements. Even when trained purely on images without explicit depth information, they typically output coherent pictures of 3D scenes. These models have the astonishing capacity to create detailed, coherent scene representations. 

However, their ability to represent depth and saliency within generated images remains unclear. Existing research primarily focuses on the output capabilities of these models, leaving a gap in comprehending their internal processing mechanics. Our project aims to delve into the diffusion process of LDMs, unraveling how they internally represent and process 3D scenes. 

This investigation is crucial as it not only enhances our understanding of AI's interpretive capabilities but also paves the way for further advancements in image synthesis. 

### Data

For this project, our training dataset consists of 617 images (512 pixels x 512 pixels) generated from Stable Diffusion v1.4. If we want to show the internal representation of our diffusion model through salient object detection, then our testing dataset consists of the salient object mask outputs from applying TRACER (\url{https://github.com/Karel911/TRACER}) to our generated images. If our goal is depth estimation, then our testing dataset consists of the monocular depth estimation outputs from applying MiDaS (\url{https://github.com/isl-org/MiDaS}) to our generated images. We have successfully obtained all training and testing datasets, but we plan to generate more images using different prompts according to the directions we hope to explore.

<img src="images/bike figures.png?raw=true"/>
