# AI tools in image analysis Workshop - youngSMLMS-2025
[Estibaliz Gómez de Mariscal](https://henriqueslab.org/pages/egdmariscal), ITQB NOVA, Oeiras, Portugal

## Overview
1.  **Hands-on deep learning using ZeroCostDL4Mic**: Image reconstruction from high-density SMLM using DeepSTORM, first published in 2018 by [Nehme et al. in Optica](https://www.google.com/url?q=https%3A%2F%2Fwww.osapublishing.org%2Foptica%2Fabstract.cfm%3Furi%3Doptica-5-4-458).
2.  **Reproducible AI-pipelines with DL4MicEverywhere**
3.  [DINOSim](https://github.com/AAitorG/napari-DINOSim): Zero-Shot Segmentation
4.  **The BioImage Model Zoo**
5.  
## 1. DeepSTORM-ZeroCostDL4Mic
Requirements 

1. **Google Colab**
2. **ZeroCostDL4Mic repository**: https://github.com/HenriquesLab/ZeroCostDL4Mic
3. Test and example data: BIN10-DeepSTORM.zip in the releases of this repository. This data is a subset of the one given in the [original publication of ZeroCostDL4Mic by von Chamier et al., Nat Comms 2021](https://www.nature.com/articles/s41467-021-22518-0)
4. Pretrained model: A pretrained deepSTORM model `smlm_18082025_v02.zip` is facilitated in the releases of this repository to speed-up the practical exercise.


## 2. DL4MicEverywhere 
Requirements 

1. **DL4MicEverywhere**: Download from [GitHub](https://github.com/HenriquesLab/DL4MicEverywhere).
   - Launch it for the first time to ensure that it works. You can try it with the notebook: `U-Net_2D_Multilabel_ZeroCostDL4Mic.ipynb`

2. **Docker**: DL4MicEverywhere will attempt to install this automatically on first launch. If this fails, download from [docker.com](https://www.docker.com/)
   - Note: Root access is required for installation

### **Step-by-step exercises to start using DL4MicEverywhere:**
[DL4MicEverywhere Workshop Guidelines - I2K 2024 ](https://gist.github.com/esgomezm/fe455b3a5c5fdd6e33c0958ddcf331ed)

## 3. DINOSim
DINOSim: Zero-shot image segmentation using DINOv2 vision transformers
GitHub repository for napari -plugin: https://github.com/AAitorG/napari-DINOSim
Data: EVs-EM.zip data in the releases of this repository
Paper: https://doi.org/10.1101/2025.03.09.642092

## 4. The BioImage Model Zoo
Requirements: 
- **Google Chrome**

Explore the [BioImage Model Zoo](https://bioimage.io/#/) and interact with its content. Recommended models: `placid-llama`, `sincere-microbe`, `loyal-squid`, `ambitious-sloth`, `powerful-chipmunk`
