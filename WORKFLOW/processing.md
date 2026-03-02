Hyperspectral Image Preprocessing Workflow
Overview

Hyperspectral data contains hundreds of contiguous spectral bands, which provide detailed information about material properties. However, raw hyperspectral imagery is affected by noise, redundancy, and atmospheric distortions. This preprocessing workflow was designed to improve data quality and ensure reliable classification and spectral analysis.

The workflow was implemented using ENVI to prepare the HSF Fooding hyperspectral dataset for feature extraction and supervised classification.

Step 1: Data Import and Visualization

The hyperspectral dataset was loaded using the .hdr and corresponding .dat files. Initial visualization of spectral bands was performed to understand the spatial distribution of features and identify noisy or corrupted bands.

This step enabled:

Verification of dataset integrity

Identification of relevant spectral regions

Understanding spatial variability.

Step 2: Signal Optimization using Minimum Noise Fraction (MNF)

Minimum Noise Fraction (MNF) rotation was applied to reduce noise and improve spectral separability. MNF performs a noise-whitening transformation followed by dimensionality reduction, which enhances meaningful spectral features.

Key objectives:

Separate signal from noise

Reduce data dimensionality

Improve classification accuracy.

The forward MNF transformation was executed, and the resulting components were analyzed to retain bands with high information content.

According to the workflow described in the project documentation, MNF significantly improved spectral quality and reliability. 

Hyperspectral Image Processing …

Step 3: Selection of Informative Components

Low-variance MNF components dominated by noise were discarded. Only components representing meaningful spectral variation were retained for further processing.

This step ensured:

Reduced redundancy

Improved computational efficiency

Better training data for classification.

Step 4: Data Preparation for Feature Extraction

The optimized MNF output was used as the input for endmember extraction and classification. This prepared dataset enabled accurate identification of pure spectral signatures.

Summary

The preprocessing stage transformed raw hyperspectral imagery into a clean and optimized dataset. By reducing noise and dimensionality, this workflow improved spectral separability and enabled reliable endmember extraction and classification.