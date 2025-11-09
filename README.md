# DNN_MINI_PROJECT_1
# Deep Neural Networks: CNN Architecture, Invariance, Feature Extraction, and Adversarial Attacks

### 🧠 M.Tech Coursework Project — IIIT Bangalore  
**Submitted by:**  
- Abhay Gotmare (MT2025702)  
- Lomesh Soni (MT2025711)  
**Date:** November 2025  

---

## 📘 Overview

This project is a consolidated study on **Deep Neural Networks (DNNs)**, focusing on four major aspects of Convolutional Neural Networks (CNNs):  
1. **Training and Analysis on CIFAR-10**  
2. **Invariance Properties of CNNs**  
3. **CNN as a Feature Extractor**  
4. **Adversarial Robustness (FGSM Attacks)**  

The experiments explore CNN performance, generalization, and vulnerability through both classical and modern deep learning methodologies.

---

## 🧩 Project Modules

### **1. Playing with CNNs on CIFAR-10**
- Compared activation functions (ReLU, Tanh, Sigmoid) and optimizers (SGD, SGD+Momentum, Adam).  
- Evaluated architectures: Baseline CNN, ComplexNet, and ResidualNet.  
- Achieved **best validation accuracy: 88.46%** with ResidualNet (ReLU + BN + Adam).  
- Demonstrated faster convergence and higher robustness with deeper, normalized models.  

---

### **2. Exploring Invariance Properties**
- Studied geometric invariance of CNNs under rotation and translation.  
- Used **Cosine Similarity**, **PCA**, and **t-SNE** to visualize feature stability.  
- Found that invariance increases with network depth but remains imperfect.  
- Suggested group-equivariant CNNs and anti-aliasing filters for better robustness.  

---

### **3. CNN as a Feature Extractor**
- Used **ResNet50 (ImageNet-pretrained)** for transfer learning on the **TF Flowers dataset (5 classes)**.  
- Extracted 2048-dimensional feature vectors and trained classical ML models:  
  - **SVM:** 71.7%  
  - **Random Forest:** 66.3%  
  - **XGBoost:** **73.6% (Best)**  
- Demonstrated effective combination of deep and traditional ML models.  

---

### **4. Adversarial Attacks and Implementation**
- Implemented **FGSM (Fast Gradient Sign Method)** for both untargeted and targeted attacks.  
- Observed severe accuracy degradation with small perturbations (ε = 0.147 for 100% attack success).  
- Highlighted DNN vulnerability due to **high-dimensional linearity** and **non-robust features**.  
- Provided mathematical formulations and visual demonstrations of attacks.  

---

## ⚙️ Implementation Details
- Frameworks: **TensorFlow / Keras, NumPy, Matplotlib, scikit-learn, XGBoost**  
- Datasets: **CIFAR-10, TF Flowers, MNIST**  
- All experiments conducted on GPU-enabled environments.  
- Code organized by module for clarity and reproducibility.

---


---

## 🧾 Citation
If you use this work or its methods, please cite:
> Gotmare, A., & Soni, L. (2025). *Deep Neural Networks: CNN Architecture, Invariance, Feature Extraction, and Adversarial Robustness*. IIIT Bangalore.

---

## 🔗 Resources
📘 Full Report: [`DNN_MINI_PROJECT_1_REPORT.pdf`](./DNN_MINI_PROJECT_1_REPORT.pdf)  
💻 Complete Code: [GitHub Repository](https://github.com/Lomesh2000/ML-Project-END-to-END)

---


