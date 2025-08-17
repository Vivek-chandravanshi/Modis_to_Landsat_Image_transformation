# 🌍 MODIS-to-Landsat Image Transformation using Autoencoder

## 📌 Project Description
This project explores the transformation of **MODIS (Moderate Resolution Imaging Spectroradiometer)** imagery into **Landsat-like imagery** using a **deep learning autoencoder**.

- **Why?**  
  MODIS provides frequent observations (daily to near-daily) but at coarse resolution (250m–1km). Landsat, on the other hand, offers finer spatial resolution (30m) but with lower revisit frequency (16 days).  
  By transforming MODIS into Landsat-like outputs, we combine the strengths of both: **high temporal + high spatial resolution**.

- **How?**  
  An **autoencoder** is trained to learn mappings from MODIS inputs to corresponding Landsat targets.  
  - The **encoder** compresses MODIS features into a compact latent representation.  
  - The **decoder** reconstructs high-resolution, Landsat-like imagery.  

- **Applications**  
  - Land use and land cover change detection  
  - Environmental monitoring  
  - Data fusion in remote sensing  

---

## 🛠 Methods

Currently implemented:
- **Autoencoder** – Learns latent feature representations of MODIS images and reconstructs Landsat-like outputs.

Planned:
- **U-Net (Coming Soon)** – Convolutional encoder-decoder with skip connections for improved spatial detail.

---
