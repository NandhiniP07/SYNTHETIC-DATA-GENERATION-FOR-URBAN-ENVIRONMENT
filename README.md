# Synthetic Data Generation for Urban Environment

## Overview
This project explores the use of **synthetic urban data** to train deep learning models for applications such as traffic sign recognition and urban object classification. Synthetic data reduces the cost and limitations of real-world data collection while improving model robustness.

---

## Approach
- Synthetic urban images with variations in lighting, blur, noise, and perspective
- Data augmentation using **Albumentations**
- **ResNet-18 (CNN)** model trained using **PyTorch**
- Transfer learning with ImageNet pretrained weights

---

## Training Details
- **Loss:** Cross-Entropy  
- **Optimizer:** Adam  
- **Epochs:** 5  
- **Input Size:** 64 × 64  
- **Framework:** PyTorch  

---

## Evaluation
- Accuracy and classification report
- Training vs validation accuracy visualization
- Sample prediction results and CSV export

---

## Conclusion
The results show that **synthetic data combined with deep learning** can effectively train urban AI models while reducing real-world data collection costs, making it suitable for smart city and autonomous driving applications.

