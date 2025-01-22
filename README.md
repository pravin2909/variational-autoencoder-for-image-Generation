# variational-autoencoder-for-image-Generation

This repository contains a project focused on Variational Autoencoders (VAEs) for analyzing the NIH Chest X-Ray dataset. The project explores tasks like denoising and generating synthetic chest X-ray images.

---

## Overview

Variational Autoencoders (VAEs) are a type of generative model that learns latent representations of input data. In this project, we applied VAEs to medical imaging to:

- Remove noise from chest X-ray images (denoising).
- Generate synthetic chest X-ray images for potential use in training machine learning models.

---

## Dataset

We used the **NIH Chest X-Ray Dataset**, a publicly available dataset with over 100,000 labeled chest X-ray images. The dataset includes various categories like normal, pneumonia, and other conditions, providing a rich resource for training and testing.

---

## Key Features

- **Denoising**: VAEs were trained to reconstruct clean images from noisy input.
- **Synthetic Image Generation**: The decoder of the VAE was used to generate realistic chest X-ray images.

---

## Installation and Requirements

To run this project, ensure you have the following installed:

- Python 3.8+
- PyTorch
- NumPy
- Matplotlib
- CUDA (for GPU acceleration)

### Install Dependencies
```bash
pip install torch torchvision numpy matplotlib
