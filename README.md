# MultispeCOD: Multispectral Camouflaged Object Detection

[![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=flat-square&logo=python)](https://python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.8%2B-FF6F00?style=flat-square&logo=tensorflow)](https://tensorflow.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

## 📋 Project Description

**MultispeCOD** is an advanced deep learning system designed to detect camouflaged objects using multispectral image analysis. The project implements a Multi-Scale Spectral Fusion CNN with attention mechanisms that analyzes seven distinct electromagnetic spectrum bands to identify objects that are specifically designed to be hidden from visual detection.

### Key Features:
- **Multispectral Analysis**: Utilizes 7 spectral bands (VIS, Blue, Green, Red, EIR, NIR, LWIR) instead of traditional RGB
- **Spectral Attention Mechanism**: AI-driven learning of optimal band combinations for detection
- **Multi-Scale Architecture**: Detects camouflaged objects at various scales using dilated convolutions
- **High Performance**: Achieves 91.7% detection accuracy with real-time processing capabilities
- **Memory Optimized**: Designed for Google Colab and resource-constrained environments

### Applications:
- Military surveillance and reconnaissance
- Wildlife monitoring and conservation
- Security and border control
- Search and rescue operations

---

## 📊 Dataset

This project uses the **MUDCAD-X (Multispectral Dataset for Camouflaged Object Detection - Extended)** dataset:

### Dataset Details:
- **Source**: Extended version of MUCAD dataset by Tobias Hupel and Peter Stütz
- **Size**: ~1.19 GB
- **Image Resolution**: 512×512 pixels (resizable to 128×128, 256×256)
- **Format**: PNG files (one per spectral band + ground truth mask)
- **Spectral Bands**: 7 bands covering visible to long-wave infrared spectrum
- **Ground Truth**: Pixel-wise binary segmentation masks

### Spectral Bands Included:
1. **VIS** - Visible spectrum (general detection)
2. **Blue** - 450-495nm (aquatic camouflage detection)
3. **Green** - 495-570nm (vegetation analysis)
4. **Red** - 620-750nm (material identification)
5. **EIR** - 700-800nm (edge infrared)
6. **NIR** - 800-1000nm (near-infrared, material composition)
7. **LWIR** - 8-14μm (thermal signatures)

### Dataset Structure:
