# Oxford-IIIT Pet Classification (CNN + Transfer Learning)

Deep learning image classification project using the Oxford-IIIT Pet Dataset (37 classes).  
This project compares a custom Convolutional Neural Network (CNN) built from scratch with a MobileNetV2 transfer learning approach.

---

## Project Overview

This project implements a complete deep learning workflow for multi-class image classification:

- Dataset loading and exploration (TensorFlow Datasets)
- Image preprocessing and normalization
- Train / Validation / Test splitting
- Model development (Custom CNN & MobileNetV2)
- Model training and evaluation
- Performance comparison
- Visualization of training curves and predictions

The goal is to analyze the performance difference between training a CNN from scratch and leveraging transfer learning with a pre-trained backbone.

---

## Dataset

- Oxford-IIIT Pet Dataset
- 37 classes (cat and dog breeds)
- Automatically downloaded using `tensorflow-datasets`

---
### Requirements:
tensorflow 
tensorflow-datasets
numpy
matplotlib
scikit-learn

---
## Models

### 1️⃣ Custom CNN
A baseline CNN architecture built from scratch:
- Conv2D + MaxPooling blocks
- Fully connected classifier
- Trained end-to-end

### 2️⃣ MobileNetV2 (Transfer Learning)
- Pre-trained on ImageNet
- Used as a feature extractor
- Custom classification head added
- Optional fine-tuning

---# oxford-pets-cnn-transfer-learning
Oxford-IIIT Pet Image Classification (Deep learning) using CNN &amp; Transfer Learning 


