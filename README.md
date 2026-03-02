# Hyperspectral-Image-Analysis

🌿 Hyperspectral Crop and Material Classification Using ENVI

This project focuses on hyperspectral image processing and classification to identify materials and vegetation conditions using spectral signatures. The objective was to develop a structured and reproducible workflow for extracting high-quality geospatial intelligence from hyperspectral datasets.

📌 Problem Statement

Hyperspectral datasets contain hundreds of spectral bands, making analysis complex due to redundancy, noise, and mixed pixels. Traditional RGB imagery is insufficient for identifying subtle material and crop stress variations.

This project demonstrates a workflow for:

Noise reduction

Spectral feature extraction

Endmember identification

Supervised classification

Spatial statistical analysis.

📊 Dataset

The HSF Fooding hyperspectral dataset was used. This dataset contains high-dimensional spectral imagery capturing material and vegetation reflectance across a wide wavelength range.

🔗 Dataset Link: (add your dataset link here)

🛠️ Tools and Platforms

ENVI for hyperspectral processing

Spectral analysis and classification

Remote sensing and geospatial techniques

🔬 Methodology
Phase 1: Signal Optimization

Minimum Noise Fraction (MNF) rotation was applied to remove noise and reduce redundancy. This step improved spectral separability and increased classification accuracy.

Key benefits:

Noise reduction

Dimensionality reduction

Improved endmember detection.

Phase 2: Endmember Extraction

Pixel Purity Index (PPI) was used to identify spectrally pure pixels representing different materials.

Key steps:

MNF-transformed data used as input

5,000 iterations to ensure statistical robustness

Thresholding to extract high-purity pixels.

Phase 3: ROI Development

Regions of Interest (ROIs) were created based on the extracted pure pixels. These ROIs were used as training samples for supervised classification.

Phase 4: Supervised Classification

Spectral Angle Mapper (SAM) was used to classify the hyperspectral data.

Advantages of SAM:

Robust to illumination changes

Effective for spectral similarity

Suitable for high-dimensional datasets.

Phase 5: Post-Classification Refinement

Majority filtering was applied to remove speckle noise and improve spatial consistency.

This improved:

Map readability

Classification accuracy

Statistical reliability.

Phase 6: Statistical and Spatial Analysis

Class statistics were extracted to quantify spatial distribution.

Key results:

Dominant material class identified

Percentage area for each class computed

Spectral class signatures analyzed.

For example, the statistical output (shown in your file on page 4) quantifies class occupancy such as “Plate” dominating with ~85% area. 

Post-Classification Refinement …

📈 Results

Accurate classification of spectral materials

Improved map quality after refinement

Clear spectral separability

Reliable statistical insights.

Spectral signature plots and classification maps are available in the results folder.

🚀 Industry Relevance

This workflow is applicable in:

Precision agriculture

Crop stress and disease detection

Soil and mineral mapping

Environmental monitoring

Food and material quality inspection

Defense and remote sensing.

⚠️ Challenges Faced

High dimensionality

Mixed pixels

Noise in spectral bands

ROI selection complexity.

🔮 Future Work

Deep learning-based hyperspectral classification

3D CNN and spectral-spatial models

Multispectral and hyperspectral fusion

Real-time UAV-based hyperspectral monitoring.
