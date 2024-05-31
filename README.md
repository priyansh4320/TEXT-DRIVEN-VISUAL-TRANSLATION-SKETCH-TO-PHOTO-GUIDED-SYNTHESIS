
# TEXT-DRIVEN VISUAL TRANSLATION: SKETCH-TO-PHOTO GUIDED SYNTHESIS

This task aims to bridge the gap between rough sketches and fully rendered images, enabling the
automatic generation of visually appealing content from minimal input. The objective of this problem is
to develop a generative model like the Diffusion Model architecture that can convert hand-drawn sketches
into detailed and realistic images.

## Approach
A neural network architecture to add spatial conditioning controls to large, pretrained
text-to-image diffusion models. ControlNet locks the production-ready large diffusion models,
and reuses their deep and robust encoding layers pretrained with billions of images as a strong
backbone to learn a diverse set of conditional controls. The neural architecture is connected
with “zero convolutions” (zero- initialized convolution layers) that progressively grow the
parameters from zero and ensure that no harmful noise could affect the finetuning. We test
various conditioning controls, e.g., edges, depth, segmentation, human pose, etc., with Stable
Diffusion, using single or multiple conditions, with or without prompts.

 
## 🔗 Research Publication
- title: Advancements in Generative Modeling: A Comprehensive Survey of GANs and Diffusion Models for Text-to-Image Synthesis and Manipulation
- Abstract: This review paper explores the two main strategies in Gen AI: GANs and Diffusion models. GANs involve the generation and discrimination of data, with a focus on their architecture, optimization techniques, and challenges like mode disintegration and instability. Diffusion models, a blend of noise diffusion and denoising, aim to rewrite the generative narrative with their high-constancy photo generation, precise distribution coverage, and scalability benefits. The paper also highlights the interaction between GANs and Diffusion models, highlighting scenarios where each model is preferred and where collaboration unlocks synergistic capabilities. The review provides a roadmap for future research, identifying key areas for exploration and development in the ever-evolving landscape of generative modeling. The manuscript serves as a comprehensive manual for researchers/practitioners looking to navigate the complex world of GANs and Diffusion strategies.

  - Paper Publication url : (https://ieeexplore.ieee.org/document/10481956/authors#authors)


## Contact Me
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/priyanshudeshmukh/)

