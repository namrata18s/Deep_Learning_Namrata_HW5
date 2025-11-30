# Deep_Learning_Namrata_HW5

# DDPM on CIFAR-10  
Implementation of Denoising Diffusion Probabilistic Models (DDPM)  
for CpSc 8430 — Deep Learning (Homework 5)

## 📌 Overview
This project implements and trains a **Denoising Diffusion Probabilistic Model (DDPM)**  
on the **CIFAR-10 (32×32)** dataset using the  
[`lucidrains/denoising-diffusion-pytorch`](https://github.com/lucidrains/denoising-diffusion-pytorch) library.

The project includes:
- Training a DDPM model from scratch  
- Generating synthetic images  
- Exporting CIFAR-10 test images to PNG  
- Computing **FID score** using `pytorch-fid`  
- Comparing results with the DDPM paper  

---
Required packages include:

torch
torchvision
denoising-diffusion-pytorch
pytorch-fid
Pillow
numpy

Compute FID Score

Using the generated images (gen5000) and exported CIFAR-10 test images:

python -m pytorch_fid gen5000 cifar10_test_images

👩‍💻 Author

Namrata Surve
Clemson University — CpSc 8430 (Fall 2025)
