# pneumonia-detection
# PneumoWatch - Pneumonia Detection using MobileNetV2

## Overview
PneumoWatch is a deep learning project developed to detect pneumonia from chest X-ray images using the MobileNetV2 architecture. The project focuses on creating a lightweight and efficient model suitable for real-time medical screening and mobile deployment.

---

## Tech Stack
- Python
- TensorFlow
- Keras
- MobileNetV2
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Seaborn
- TFLite

---

## Features
- Pneumonia detection from chest X-ray images
- Deep learning model using MobileNetV2
- Image preprocessing using OpenCV
- Training and validation visualization
- Model optimization using TensorFlow Lite
- Real-time prediction support

---

## Dataset
- Chest X-ray image dataset
- 5800+ chest X-ray images used for training and testing
- Classes:
  - NORMAL
  - PNEUMONIA

---

## Project Workflow
1. Load and preprocess chest X-ray images
2. Create training, validation, and testing datasets
3. Normalize image data
4. Build deep learning model using MobileNetV2
5. Train model with Early Stopping
6. Evaluate model performance
7. Convert model into TFLite format
8. Perform real-time predictions

---

## Model Architecture
- MobileNetV2 (Pretrained on ImageNet)
- Batch Normalization
- Dropout Layers
- Dense Layers
- Binary Classification Output Layer

---

## Data Visualization
The project includes:
- Category distribution graphs
- Sample image visualization
- Accuracy and loss graphs
- Prediction result visualization

---

## Results
- Achieved 94% validation accuracy on chest X-ray classification
- Lightweight and fast model performance
- Efficient deployment using TensorFlow Lite
- Reliable pneumonia classification results

---

## Files Included
