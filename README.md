
# 🧠 Hybrid Deep Learning Framework for Pneumonia Detection (VGG-19 + ResNet50)

This project implements a **hybrid deep learning model** for automatic detection of **pneumonia** using **chest X-ray images**, leveraging the strengths of **VGG-19** and **ResNet50** for enhanced performance.

---

## 🎯 Objective

To develop a robust, high-accuracy model for binary classification of X-ray images into:
- ✅ **Normal**
- ❌ **Pneumonia**

---

## 🏗️ Architecture

The model combines:
- 🔬 **VGG-19** for fine-grained feature extraction
- 🧱 **ResNet50** for deeper residual learning
- 🧠 Fusion of both models' outputs followed by a **Dense + Softmax** layer for final classification

---

## 🧪 Data Augmentation Techniques Used

To improve generalization and prevent overfitting:
- 📐 Random Rotation
- 🔄 Horizontal Flip
- 🔍 Zoom Range
- ✂️ Width & Height Shift
- 💡 Rescaling (Normalization)

---

## 📊 Results

### ✅ Accuracy
- **Training Accuracy:** ~95%
- **Validation Accuracy:** ~90%
- Achieved using data augmentation + hybrid model design

### 📉 Confusion Matrix
please go through to uploded paper above.
