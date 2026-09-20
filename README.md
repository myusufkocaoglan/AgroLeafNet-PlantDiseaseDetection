<div align="center">

# 🌿 AgroLeafNet: Deep Learning-Based Plant Disease Detection

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Framework](https://img.shields.io/badge/Framework-TensorFlow%20%2F%20Keras-orange.svg?logo=tensorflow&logoColor=white)](https://tensorflow.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green.svg?logo=opencv&logoColor=white)](https://opencv.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<p align="center">
  <b>An automated, deep learning-powered computer vision pipeline designed for early diagnosis and classification of agricultural plant leaf diseases.</b>
</p>

</div>

---

## 📌 Overview

**AgroLeafNet** is an end-to-end computer vision and deep learning solution aimed at assisting agronomists, farmers, and researchers in early plant disease detection. By leveraging Convolutional Neural Networks (CNNs) and transfer learning architectures, the model classifies crop conditions and identifies visible pathologies directly from leaf images.

### Key Highlights
- **Automated Diagnosis:** Rapid classification of healthy vs. diseased plant leaves across multiple crop species.
- **Robust Preprocessing:** Image enhancement, noise reduction, and data augmentation to handle varying field conditions.
- **High Accuracy & Generalization:** Fine-tuned transfer learning backbones with optimized hyper-parameters.
- **Modular Pipeline:** Extensible architecture ready for desktop, mobile (Edge / TFLite), or IoT edge deployment.

---

## 🏗️ Project Architecture
```text
AgroLeafNet-PlantDiseaseDetection/
│
├── data/                     # Dataset directory (raw & preprocessed images)
├── models/                   # Saved model weights (.h5, .pt, or .tflite)
├── notebooks/                # Jupyter / Colab exploratory notebooks
├── src/                      # Source code (preprocessing, model, train, predict)
├── requirements.txt          # Project dependencies
└── README.md                 # Project documentation
```
