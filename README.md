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

Repository with all materials:  
👉 [https://github.com/esgomezm/AI-Workshop-youngSMLMS-2025](https://github.com/esgomezm/AI-Workshop-youngSMLMS-2025)  

Data and pretrained models:  
👉 [Workshop Data Release](https://github.com/esgomezm/AI-Workshop-youngSMLMS-2025/releases/tag/data)  

---

## 1. 🔬 DeepSTORM with ZeroCostDL4Mic  

**Goal:** Learn hands-on image reconstruction from high-density SMLM using DeepSTORM.  

### Requirements
1. Google Colab  
2. [ZeroCostDL4Mic repository](https://github.com/HenriquesLab/ZeroCostDL4Mic)  
3. Test/Example Data:  
   - **BIN10-DeepSTORM.zip** (provided in the [workshop data release](https://github.com/esgomezm/AI-Workshop-youngSMLMS-2025/releases/tag/data))  
4. Pretrained Model:  
   - **smlm_18082025_v02.zip** (available in the same data release)   

---

## 2. 🖥️ DL4MicEverywhere  

**Goal:** Explore reproducible and portable AI workflows for bioimage analysis.  

### Requirements  
1. [DL4MicEverywhere](https://github.com/HenriquesLab/DL4MicEverywhere)  
   - Test with: **U-Net_2D_Multilabel_ZeroCostDL4Mic.ipynb** (included in the repository)  
2. Docker  
   - Installed automatically at first launch (if not, download from [docker.com](https://www.docker.com/))  
   - ⚠️ Requires **root access** for installation  

### Step-by-Step Exercises  
Follow the detailed walkthrough provided in:  
[DL4MicEverywhere Workshop Guidelines – I2K 2024](https://gist.github.com/esgomezm/fe455b3a5c5fdd6e33c0958ddcf331ed)  

---

## 3. 🧩 DINOSim: Zero-Shot Segmentation  

**Goal:** Try transformer-based segmentation with no manual annotations.  

- Tool: [napari-DINOSim](https://github.com/AAitorG/napari-DINOSim) (napari plugin)  
- Data: **EVs-EM.zip** (available in the [workshop data release](https://github.com/esgomezm/AI-Workshop-youngSMLMS-2025/releases/tag/data))  
- Paper: [DOI:10.1101/2025.03.09.642092](https://doi.org/10.1101/2025.03.09.642092)  

---

## 4. 🌐 The BioImage Model Zoo  

**Goal:** Discover and test community models for imaging tasks.  

### Requirements
- Browser: **Google Chrome**  

### Recommended Exploration  
Visit: [bioimage.io](https://bioimage.io/#/) and try pretrained models, such as:  
- **placid-llama**  
- **sincere-microbe**  
- **loyal-squid**  
- **ambitious-sloth**  
- **powerful-chipmunk**  

---

## ✅ Final Notes  
- Please ensure **Google Colab and Docker** are set up in advance.  
- All required datasets and pretrained models are bundled in the [workshop data release](https://github.com/esgomezm/AI-Workshop-youngSMLMS-2025/releases/tag/data).  
- Tutorials are structured to be progressive: start with **DeepSTORM**, move to **DL4MicEverywhere**, then explore **DINOSim** and the **Model Zoo**.  

---

✨ **By the end of this workshop, participants will have hands-on experience with deep learning pipelines, zero-shot segmentation, and models from the BioImage Model Zoo.**
