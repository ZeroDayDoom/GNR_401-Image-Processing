# GNR_401-Image-Processing
## Hyperspectral Image Enhancement — Indian Pines

**Author:** Ankit Rewar 

**Course / Project:** Hyperspectral Image Processing (assignment)  

**Dataset:** Indian Pines (provided as `.mat`)  

---

## Project summary

This repository contains an implementation of fundamental image processing and enhancement algorithms applied to a hyperspectral image cube (Indian Pines). All core image-processing algorithms were implemented from scratch (no library functions used for the core transforms), as required by the project brief. :contentReference[oaicite:0]{index=0}

Implemented algorithms:
- Log transform
- Gamma correction
- Contrast stretching
- Histogram equalization
- Convolution filters:
  - Mean (average) filter
  - Gradient filters (edge detection)

---

## Files in this repository

- `notebooks/hyperspectral_processing.ipynb` — Jupyter notebook with end-to-end code, experiment cells and visualizations.  
  **Local notebook file (uploaded):** `/mnt/data/95eb6d41-b5b2-4b59-a997-e7e87f6fb186.ipynb`
- `data/Indian_Pines.mat` — Dataset (hyperspectral cube).  
  **Local dataset file (uploaded):** `/mnt/data/2eaba549-9ff6-4d8b-8a15-0e5f5d241575.mat`
- `docs/project_spec.pdf` — Original project specification. :contentReference[oaicite:1]{index=1}  
  **Local PDF (uploaded):** `/mnt/data/c78ef2f4-7362-4d07-8f39-0e065cca4e16.pdf`
- `README.md` — This file.
- `requirements.txt` — (See instructions below to create; minimal packages required for I/O and plotting.)

> Note: Core algorithm implementations avoid external library shortcuts; standard libraries such as `numpy`, `scipy` (for `.mat` I/O only), and `matplotlib` are used for array ops, file I/O and plotting.

---

## How to run

1. Clone this repository:
   ```bash
   git clone <your-repo-url>
   cd <repo-name>
