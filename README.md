### Introduction
This repository contains the implementation of a video dehazing project using the Dark Channel Prior methodology. The project aims to remove haze from video footage, enhancing visual clarity and improving overall image quality.

### Methodology
#### The video dehazing process involves several key steps:
#### ->Dark Channel Computation: Calculating the dark channel of each frame to estimate the haze thickness.
#### ->Atmospheric Light Estimation: Estimating the atmospheric light to determine the intensity of haze.
#### ->Transmission Map Generation: Generating a transmission map to represent the amount of haze in each pixel.
#### ->Guided Filtering and Transmission Refinement: Applying advanced techniques such as guided filtering and transmission refinement to enhance visual clarity and remove haze effectively.

### Results
The model works effectively on real-time videos, successfully removing haze and improving visual clarity. Below are the sample images comparing the input and output frames:
![Screenshot 2024-04-08 131044](https://github.com/LoheshM/Dark-Channel-Video-Dehazing-/assets/116341584/87166864-5eaf-403c-8003-4046128fabfe)
![Screenshot 2024-04-08 131127](https://github.com/LoheshM/Dark-Channel-Video-Dehazing-/assets/116341584/92ff75a8-e03a-4399-9658-af31d3cb6f16)
![Screenshot 2024-04-08 130942](https://github.com/LoheshM/Dark-Channel-Video-Dehazing-/assets/116341584/b70be5a6-0a5e-4d0b-8ada-d0900a6abc41)
![Screenshot 2024-04-08 130852](https://github.com/LoheshM/Dark-Channel-Video-Dehazing-/assets/116341584/cd74e8b0-0314-432c-a45e-eacab7464ea6)


