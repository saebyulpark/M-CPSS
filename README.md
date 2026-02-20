# M-CPSS: Multimodal Creative Product Semantic Scale

## Introduction
This repository provides resources, code, and documentation for the study **"A Large-Scale Multimodal Framework for Mapping Artistic Creativity: How Do Human and AI Art Differ?"**, presented at **CHI 2026**. This study introduces **M-CPSS**, a computational framework that bridges psychological theories of creativity with vision--language models for large-scale, interpretable analysis of artistic creativity. By aligning artworks with the **Creative Product Semantic Scale (CPSS)** within a CLIP-based image--text embedding space, our approach represents each artwork as a structured profile of creative attributes.

![Teaser Figure](https://drive.google.com/uc?id=1uoVFtwXUlGZwe0ZqlEyEQ9NAcAoRGd88)

*Example creativity profiles of individual artworks based on the M-CPSS framework. The profiles illustrate how artistic creativity can be represented by embedding artworks and creative attributes into a shared vision--text multimodal embedding space.*


Please refer to the full paper for an in-depth analysis of our findings and methodology: **[Paper Link - TBA]**

## Tutorial
The tutorial provides a step-by-step guide to implementing the M-CPSS pipeline using Python. It covers the entire workflow from extracting multimodal features to generating creativity profiles and constructing similarity networks.

* **[Tutorial - TBA]**: Full implementation including CLIP feature extraction, bipolar softmax scoring, and hierarchical profile generation.

## Dataset
Our analysis is conducted using the **AI-ArtBench** dataset, which provides a balanced collection of human-created and AI-generated artworks with consistent style annotations.

* **Data Source**: The original images and metadata can be downloaded from the official repository: [[AI-ArtBench on Kaggle]](https://www.kaggle.com/datasets/ravidussilva/real-ai-art).
* **Scope**: 185,015 images spanning 10 artistic styles and 3 generative sources (Human, Latent Diffusion, Stable Diffusion).

## Experimental Results
![Result Figure](https://drive.google.com/uc?id=1mZkMRxsveIa8jxVCxLv8ilHRb10EVvmE)
*Overview of M-CPSS results: (R1) Creativity profile differences, (R2) Style-conditioned differences, and (R3) Creativity network structure.*

## Contact
For questions or further information regarding the M-CPSS framework, please contact **Saebyul Park** ([saebyulsb@gmail.com](mailto:saebyulsb@gmail.com)).

---
**Supplementary Materials**: Detailed experimental results, piecewise scaling calibration, and extended network statistics are available in the **[Supplementary PDF - TBA]**.
