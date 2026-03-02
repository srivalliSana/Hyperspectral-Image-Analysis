# 🌿 Hyperspectral Image Processing and Classification

This project focuses on hyperspectral image analysis to identify materials and vegetation conditions using spectral signatures. The workflow demonstrates a structured approach to hyperspectral preprocessing, feature extraction, and classification.

---

## 📌 Problem Statement  

Hyperspectral data contains hundreds of spectral bands, making analysis complex due to redundancy, noise, and mixed pixels. Traditional RGB and multispectral imagery are often insufficient for identifying subtle variations in crop stress and material properties.

This project develops a reproducible workflow for extracting actionable insights from hyperspectral datasets.

---

## 🚀 Project Impact  

This work demonstrates how hyperspectral imaging enables:

- Early detection of plant stress and disease  
- Accurate material and vegetation classification  
- Precision agriculture and resource optimization  
- Environmental monitoring and sustainability  
- Improved decision-making in AgTech and remote sensing  

---

## 📊 Dataset  

The HSF Fooding hyperspectral dataset was used in this project. The dataset contains high-dimensional spectral imagery capturing reflectance across a wide wavelength range.

🔗 Dataset Link:  https://cogsys.cs.uni-tuebingen.de/webprojects/DeepHS-Fruit-2023-Datasets/

---

## 🛠️ Tools and Platforms  

- ENVI for hyperspectral processing  
- Spectral analysis and classification  
- Geospatial and remote sensing workflows  

---

## 🔬 Methodology  

### Phase 1: Signal Optimization  
Minimum Noise Fraction (MNF) rotation was applied to reduce noise and improve spectral separability.

### Phase 2: Endmember Extraction  
Pixel Purity Index (PPI) was used to identify pure spectral pixels.

### Phase 3: ROI Development  
Regions of Interest were created based on pure pixels for supervised classification.

### Phase 4: Supervised Classification  
Spectral Angle Mapper (SAM) was used for classification due to its robustness in high-dimensional datasets.

### Phase 5: Post-Classification Refinement  
Majority filtering was applied to remove speckle noise and improve spatial consistency.

### Phase 6: Statistical Analysis  
Class statistics were extracted to quantify spatial distribution.

---

## 💡 My Contributions  

- Developed a structured hyperspectral processing workflow  
- Applied MNF and PPI for signal optimization  
- Extracted spectral endmembers  
- Created ROIs for supervised classification  
- Performed SAM-based classification  
- Conducted post-classification refinement  
- Generated statistical and spatial insights  

---

## 🌿 Key Techniques Used  

- MNF noise reduction  
- Pixel Purity Index  
- Endmember extraction  
- Spectral Angle Mapper  
- Majority filtering  
- Statistical analysis  

---

## 📊 Key Observations  

- MNF improved spectral separability  
- PPI enabled identification of reliable training samples  
- SAM produced meaningful classification maps  
- Post-classification refinement improved accuracy  
- Statistical analysis provided quantitative insights  

---

## 🌍 Industry Use Cases  

- Precision agriculture  
- Crop disease and stress detection  
- Soil and mineral mapping  
- Food and material quality inspection  
- Environmental monitoring  
- Defense and remote sensing  

---

## ⚠️ Challenges Faced  

- High dimensionality and redundancy  
- Mixed pixels  
- Noise and atmospheric interference  
- ROI selection complexity  

---

## 🔮 Future Scope  

- Deep learning-based hyperspectral classification  
- Spectral-spatial CNN models  
- Multispectral and hyperspectral data fusion  
- UAV-based hyperspectral monitoring  
- Cloud-based geospatial analytics  

---

## 📬 Contact  

For collaboration or research discussions in hyperspectral imaging, AI, and agriculture, feel free to connect.
