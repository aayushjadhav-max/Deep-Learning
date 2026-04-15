# ⚡ Solar Panel Fault Detection using EfficientNetB0

This project implements a deep learning-based system to detect faults in solar panels using image classification.

## 🚀 Features
- Transfer Learning with EfficientNetB0
- Multi-class classification (6 classes)
- Data Augmentation
- Class imbalance handling
- Performance visualization dashboard

## 📊 Classes
- Bird-drop
- Clean
- Dusty
- Electrical-damage
- Physical-Damage
- Snow-Covered

## 📈 Results
- Accuracy: ~82%
- Strong performance across multiple classes

## 🧠 Model Architecture
EfficientNetB0 → GlobalAveragePooling → Dense Layers → Softmax

## 📦 Installation
```bash
pip install -r requirements.txt
