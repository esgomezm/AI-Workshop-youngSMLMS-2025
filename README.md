# AI Tools in Image Analysis Workshop – youngSMLMS 2025  
*[Estibaliz Gómez de Mariscal](https://henriqueslab.org/pages/egdmariscal), ITQB NOVA, Oeiras, Portugal*  

---

## 📌 Overview  
This hands-on workshop introduces participants to modern AI tools for bioimage analysis. We will explore deep learning frameworks, reproducible pipelines, segmentation methods, and community-driven resources.  

1. **Hands-on Deep Learning with ZeroCostDL4Mic**  
   - Image reconstruction in SMLM using **DeepSTORM** ([Nehme et al., Optica 2018](https://www.osapublishing.org/optica/abstract.cfm?uri=optica-5-4-458))  

2. **Reproducible AI-pipelines with DL4MicEverywhere**  

3. **Zero-Shot Segmentation with DINOSim**  

4. **Exploration of the BioImage Model Zoo**  

Data and pretrained models:  
👉 [Workshop Data](https://github.com/esgomezm/AI-Workshop-youngSMLMS-2025/releases/tag/data)  

---

## 1. 🔬 DeepSTORM with ZeroCostDL4Mic  

**Goal:** Learn hands-on image reconstruction from high-density SMLM using DeepSTORM.  

### Requirements
1. Google Colab and ~5GB of free space in Google Drive
2. [ZeroCostDL4Mic repository](https://github.com/HenriquesLab/ZeroCostDL4Mic)  
3. Test/Example Data accessible from Google Drive. Please upload the unzipped folder:  
   - **BIN10-DeepSTORM.zip** (provided in the [workshop data release](https://github.com/esgomezm/AI-Workshop-youngSMLMS-2025/releases/tag/data))  
4. Pretrained Model accessible from Google Drive. Please upload the unzipped folder:  
   - **smlm_18082025_v02.zip** (provided in the [workshop data release](https://github.com/esgomezm/AI-Workshop-youngSMLMS-2025/releases/tag/data))  

---

## 2. 🖥️ DL4MicEverywhere  

**Goal:** Explore how to build reproducible and portable AI workflows. I will show how to use it step by step rather than going through a hands-on. 

### Requirements  
1. [DL4MicEverywhere](https://github.com/HenriquesLab/DL4MicEverywhere)  
   - Test with: **U-Net_2D_Multilabel_ZeroCostDL4Mic.ipynb** 
2. Docker  
   - Installed automatically at first launch (if not, download from [docker.com](https://www.docker.com/))  
   - ⚠️ Requires **root access** for first time installation  

### Step-by-Step Exercises  
Follow the detailed walkthrough provided in:  
[DL4MicEverywhere Workshop Guidelines – I2K 2024](https://gist.github.com/esgomezm/fe455b3a5c5fdd6e33c0958ddcf331ed)  

---

## 3. 🧩 DINOSim: Zero-Shot Segmentation  

**Goal:** Try transformer-based ZeroShot segmentation with little manual prompting.  

- Tool: [napari-DINOSim](https://github.com/AAitorG/napari-DINOSim) (napari plugin) installed locally
- Data: **EVs-EM.zip** downloaded locally (available in the [workshop data](https://github.com/esgomezm/AI-Workshop-youngSMLMS-2025/releases/tag/data))  
- Paper: A. González-Marfil, E. Gómez-de-Mariscal, I. Arganda-Carreras, DINOSim: Zero-Shot Object Detection and Semantic Segmentation on Electron Microscopy Images, bioRxiv 2025 [DOI:10.1101/2025.03.09.642092](https://doi.org/10.1101/2025.03.09.642092)  

---

## 4. 🌐 The BioImage Model Zoo  

**Goal:** Discover and test community models for imaging tasks.  

### Requirements
- Browser: **Google Chrome**  

### Recommended Exploration  
Visit: [bioimage.io](https://bioimage.io/#/) and try test-running pretrained models on the browser, such as:  
- **placid-llama**  
- **sincere-microbe**  
- **loyal-squid**  
- **ambitious-sloth**  
- **powerful-chipmunk**  

---

## ✅ Final Notes  
- Please ensure you have an internet connection  
- For any questions, you can contact me directly by email.
---
