# 🌱 Plant Leaf Disease Detection using Hybrid Deep Learning

## 📌 Overview

This project presents a **hybrid deep learning approach** for detecting and classifying plant leaf diseases using image data. The model combines the strengths of **EfficientNetV2-S (CNN)** and **MobileViTv2 (Transformer)** to capture both **local features (texture, spots)** and **global patterns (leaf structure)**.

To further enhance performance, an **adaptive feature fusion mechanism** is used to dynamically balance these features. Additionally, **Grad-CAM visualization** is implemented to make the model's predictions more interpretable.

---

## 🚀 Key Features

- ✅ Hybrid CNN–Transformer architecture  
- ✅ EfficientNetV2-S for powerful feature extraction  
- ✅ MobileViTv2 with Multi-Head Self-Attention  
- ✅ Adaptive Feature Fusion for better representation  
- ✅ Data augmentation to improve generalization  
- ✅ Grad-CAM for model interpretability  
- ✅ High performance (~95% accuracy)

---

## 🧠 Model Architecture

The model consists of two main branches:

### 🔹 1. CNN Branch (EfficientNetV2-S)
- Pretrained on ImageNet  
- Extracts deep spatial features  
- Most layers frozen for efficiency  

### 🔹 2. Transformer Branch (MobileViTv2)
- Uses Multi-Head Self-Attention  
- Captures global dependencies in images  

### 🔹 3. Adaptive Fusion
- Combines CNN and Transformer features  
- Learns the importance of each feature dynamically  

### 🔹 4. Classification Head
- Fully connected layers  
- Dropout + Batch Normalization  
- Softmax output for classification  

---

## 📂 Dataset

- Dataset consists of **plant leaf images categorized into multiple classes** (diseased + healthy).
- Directory structure:
