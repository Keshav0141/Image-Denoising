# 🖼️ Image Denoising using Deep Learning

This repository contains a Jupyter Notebook (`Image-Denoising_.ipynb`) that demonstrates how to perform **image denoising** using **Deep Learning** techniques.  
The project focuses on removing noise from images while preserving important details like edges and textures.

---

## 🎯 Objective
- Add noise to clean images (synthetic dataset generation).  
- Train a deep learning model to remove noise.  
- Compare noisy vs denoised outputs.  
- Evaluate reconstruction quality using quantitative metrics.  

---

## 📌 Key Features
- **Data Preparation**  
  - Load dataset (e.g., MNIST, CIFAR-10, custom images).  
  - Generate noisy images by adding Gaussian / Salt & Pepper noise.  
  - Normalize and preprocess images.  

- **Model Architectures**  
  - Convolutional Autoencoder for denoising.  
  - Optionally compare with traditional filters (Median, Gaussian blur).  

- **Training**  
  - Loss functions: Mean Squared Error (MSE), Mean Absolute Error (MAE).  
  - Optimizers: Adam, RMSprop.  
  - Epochs with early stopping to prevent overfitting.  

- **Evaluation & Visualization**  
  - Compare noisy, clean, and denoised images side by side.  
  - Metrics: PSNR (Peak Signal-to-Noise Ratio), SSIM (Structural Similarity Index).  
  - Training vs validation loss curves.  

---
