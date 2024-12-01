# Development of Vision Transformer-Based Models for Brain Tumor Classification  

This repository contains the implementation of a machine learning project aimed at **accurately classifying brain tumors** from MRI images using **Vision Transformer (ViT) models**. The project leverages advanced deep learning techniques to enhance diagnostic accuracy and efficiency in medical imaging.  

---

## **Project Overview**  
Brain tumor classification is a critical task in medical diagnostics. This project focuses on improving the accuracy and robustness of brain tumor detection by implementing and fine-tuning Vision Transformer models. The classification includes four categories:  
- Glioma  
- Meningioma  
- Pituitary  
- No Tumor  

By leveraging balanced datasets and cutting-edge model architectures, this project aims to support healthcare professionals in making informed decisions for treatment planning.  

---

## **Key Features**  
- **Advanced Model Architecture:**  
  - Implementation of multiple ViT models (ViT-B16, ViT-B32, ViT-L16, ViT-L32).  
  - Integration of ResNet-50 as a backbone for ViT-B32, reducing computational costs while maintaining accuracy.  

- **Robust Preprocessing Pipeline:**  
  - Applied data augmentation techniques like random rotation, flipping, color jitter, and z-score normalization to improve model generalization.  

- **High Accuracy:**  
  - Achieved 99.16% accuracy with ViT-B16, ensuring reliable classification results.  

- **Optimized Performance:**  
  - Used AdamW optimizer, dropout regularization, and early stopping to prevent overfitting and enhance convergence.  

- **Real-World Applicability:**  
  - Demonstrates potential for clinical deployment, aiding radiologists in accurate and efficient tumor detection.  

---

## **Technologies Used**  
- Python  
- Vision Transformers (ViTs)  
- TensorFlow/PyTorch  
- Google Colab for model training and evaluation  

---

## **Datasets**  
The project uses balanced datasets, including:  
1. **Kaggle Dataset:** MRI images of brain tumors.  
2. **Br35H Dataset:** Balanced tumor types for better generalization.  
3. **SARTAJ Dataset:** Additional MRI images to enhance performance.  

---
 
