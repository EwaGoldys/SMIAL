# 🔬 Example Multispectral Microscopy Dataset for SMIAL

This repository contains example autofluorescence multispectral imaging data for the following cell lines:

- **142BR** (fibroblast)  
- **COLO679** (melanoma)  
- **A374** (melanoma)

Each cell line includes **four example images**, and **each image contains 5 spectral channels** acquired using a multispectral fluorescence microscope.

In addition to the cell images, the dataset includes **example background and calibration image files** used in the preprocessing step.


---

## 📂 File Types

- **`.tiff`** – Raw multispectral image stacks  
- **`.mat`** – MATLAB files containing image data and processed SMIAL outputs  
- **Calibration/Background Files** – `.tiff` or `.mat` images used for background subtraction and spectral correction

---

---

## ⚙️ SMIAL Output Contents

Each `.mat` file includes a `SMIAL` output folder with example results from different stages of the pipeline:

1. **Preprocessing** – Smoothing and background subtraction
2. **Feature Generation** – Spectral, textural, and morphological feature extraction  
3. **Data Cleaning & Statistics** – Insignificant and correlation filtering  
4. **Feature Analysis** – Feature selection, feature extraction and classification, and performance evaluation

---

## 🧭 Cell Masks

All datasets include corresponding **cell masks** for segmentation and region-based analysis.

---

## 📦 Usage

These examples are intended for testing and demonstration of the SMIAL pipeline.
