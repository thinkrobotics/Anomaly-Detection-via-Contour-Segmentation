# Anomaly Detection using ResNet50 Feature Extraction

This repository contains a Python implementation for anomaly detection in images using feature extraction from a pre-trained ResNet50 model. The approach is based on comparing test image features against a memory bank of normal image features.

## Table of Contents
- [Overview](#overview)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Methodology](#methodology)
- [Results](#results)
- [Evaluation](#evaluation)
- [Visualization](#visualization)
- [License](#license)

## Overview

This script implements an unsupervised anomaly detection system that:
1. Extracts feature maps from a pre-trained ResNet50 model
2. Builds a memory bank of normal image features
3. Compares test images against the memory bank using nearest neighbor search
4. Detects anomalies based on distance metrics
5. Provides both image-level and pixel-level anomaly detection

## Requirements

- Python 3.7+
- PyTorch 1.8+
- Torchvision
- NumPy
- Matplotlib
- scikit-learn
- tqdm
- PIL (Python Imaging Library)
- OpenCV (for visualization)

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/anomaly-detection.git
cd anomaly-detection
