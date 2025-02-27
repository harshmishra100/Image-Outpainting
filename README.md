# Image Outpainting for Agricultural Datasets

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/Python-3.8%2B-green.svg)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-red.svg)](https://pytorch.org/)

A GAN-based solution for extending incomplete crop images using **residual skip connections** and **dilated convolutions**, designed to enhance agricultural analysis capabilities.


## 📌 Overview
Addresses the challenge of incomplete crop images in agricultural datasets by:
- Generating **realistic image extensions** beyond original boundaries
- Enabling better disease prediction and growth pattern analysis
- Using **hybrid residual skip connections** for feature preservation

## 🚀 Key Features
- **GAN Architecture** with U-Net-like generator
- **Dilated convolutions** for expanded receptive fields
- Dual **local + global discriminators** for consistency
- **MSE 0.0164 | MAE 0.0756** on Kaggle rice dataset
- Progressive training for GAN stability

## 📥 Installation
1. Clone repository:
```bash
git clone https://github.com/yourusername/image-outpainting.git
cd image-outpainting
