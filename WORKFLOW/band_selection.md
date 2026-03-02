Spectral Band Selection and Endmember Identification Workflow
Overview

Hyperspectral datasets often contain redundant and mixed spectral information. Identifying pure spectral signatures, or endmembers, is essential for accurate classification. This workflow focused on isolating pure pixels and creating training samples for supervised classification.

The methodology ensures reproducible and scientifically robust hyperspectral analysis.

Step 1: Pixel Purity Index (PPI)

The Pixel Purity Index (PPI) algorithm was applied to the MNF-transformed dataset to identify spectrally pure pixels.

PPI projects spectral data onto random vectors multiple times to locate pixels that consistently represent extreme spectral responses.

Key implementation details:

MNF output used as input

Iteration count set to 5,000 to improve statistical robustness

Thresholding applied to select high-purity pixels.

This process enabled identification of reliable training samples. The requirement for high iteration counts ensures stable and representative endmembers. 

Hyperspectral Image Processing …

Step 2: Endmember Visualization

The resulting PPI image was analyzed to locate clusters of pure pixels. These clusters represent distinct material or vegetation classes within the scene.

This step enabled:

Spectral separability

Improved classification accuracy

Reliable feature interpretation.

Step 3: ROI Creation

Regions of Interest (ROIs) were manually defined using the pure pixels identified during PPI analysis. Each ROI corresponded to a specific material class such as vegetation, soil, or other target objects.

Key considerations:

Accurate labeling of each ROI

Selection of spatially representative samples

Avoidance of mixed pixels.

These ROIs served as training data for supervised classification.

Step 4: Supervised Classification using Spectral Angle Mapper (SAM)

The Spectral Angle Mapper algorithm was applied to classify the hyperspectral dataset based on spectral similarity.

Advantages of SAM:

Robust to illumination variations

Effective for high-dimensional data

Physically interpretable spectral comparison.

Step 5: Post-Classification Refinement

The classified output was refined using majority filtering to reduce speckle noise and improve spatial consistency. This step ensured logical grouping of pixels and improved map readability.

This post-classification process was critical for generating reliable spatial statistics. 

Post-Classification Refinement …

Step 6: Statistical Analysis

Class statistics were extracted to quantify spatial distribution. The percentage area occupied by each class was computed to support decision-making and environmental analysis.

This enabled:

Quantitative interpretation

Class comparison

Reporting and documentation.

Summary

The spectral band selection and endmember workflow enabled accurate hyperspectral classification and improved interpretability of results. This approach ensured that the final output was both scientifically reliable and suitable for real-world applications.