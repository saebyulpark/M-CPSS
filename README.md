# M-CPSS: Multimodal Creative Product Semantic Scale

## Introduction
This repository provides resources, code, and documentation for the study **"A Large-Scale Multimodal Framework for Mapping Artistic Creativity: How Do Human and AI Art Differ?"**, presented at **CHI 2026**. This study introduces **M-CPSS**, a computational framework that bridges psychological theories of creativity with vision--language models for large-scale, interpretable analysis of artistic creativity. By aligning artworks with the **Creative Product Semantic Scale (CPSS)** within a CLIP-based image--text embedding space, our approach represents each artwork as a structured profile of creative attributes.

![Teaser Figure](https://drive.google.com/uc?id=1uoVFtwXUlGZwe0ZqlEyEQ9NAcAoRGd88)

*Example creativity profiles of individual artworks based on the M-CPSS framework. The profiles illustrate how artistic creativity can be represented by embedding artworks and creative attributes into a shared vision--text multimodal embedding space.*


Please refer to the full paper for an in-depth analysis of our findings and methodology: **[Paper Link - TBA]**

## Tutorial
The tutorial provides a step-by-step guide to implementing the M-CPSS pipeline using Python. It covers the entire workflow from extracting multimodal features to generating creativity profiles and constructing similarity networks.

* **[Colab Tutorial: Interactive M-CPSS Creativity Profiling Demo](https://colab.research.google.com/drive/1qa7X1LbixoXdMUD-Cco1B1v9vEap3rku?usp=sharing)**
* **[Web Demo: M-CPSS Analyzer](https://gurajun-m-cpss-analyzer.hf.space/)**
  
## Dataset
Our analysis is conducted using the **AI-ArtBench** dataset, which provides a balanced collection of human-created and AI-generated artworks with consistent style annotations.

* **Data Source**: The original images and metadata can be downloaded from the official repository: [[AI-ArtBench on Kaggle]](https://www.kaggle.com/datasets/ravidussilva/real-ai-art).
* **Scope**: 185,015 images spanning 10 artistic styles and 3 generative sources (Human, Latent Diffusion, Stable Diffusion).

## Experimental Results
![Result Figure](https://drive.google.com/uc?id=19VZEfe3giLah27n0bxG5NuMncppGcQcs)  
*Overview of M-CPSS results (R3): Structural organization of creativity-similarity networks. Our analysis reveals that **human-created art** demonstrates a more semantically diverse and cross-stylistically organized structure, whereas **AI-generated art** tends to exhibit more structurally clustered and stylized patterns. For more detailed results and comprehensive analysis (R1, R2), please refer to our full paper.*

## Contact
For questions or further information regarding the M-CPSS framework, please contact:
* **Saebyul Park** ([saebyulsb@gmail.com](mailto:saebyulsb@gmail.com))
* **Jiye Jung** ([jujiy100@uni-duesseldorf.de](mailto:jujiy100@uni-duesseldorf.de))
---
**Supplementary Materials**: Additional qualitative examples, statistical analyses, implementation details, and extended experimental results are available in the  
**[Supplementary PDF](https://drive.google.com/file/d/1JKYSwweO_emZj_3ac6OF1QTAwsmjEMrC/view?usp=sharing)**.
