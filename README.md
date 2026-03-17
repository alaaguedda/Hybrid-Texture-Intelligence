# 🧠 Hybrid Texture Intelligence Framework

### Multi-Paradigm Texture Classification using GLCM, LBP, Machine Learning, CNNs, and Transfer Learning

---

## 📌 Overview

This project presents a **comprehensive and hybrid approach to texture classification**, combining:

* Classical **handcrafted texture features**
* Traditional **machine learning models**
* Deep learning with **Convolutional Neural Networks (CNNs)**
* **Transfer learning** using a pretrained ResNet50 model

The goal is to **analyze and compare different paradigms** of image understanding, from statistical descriptors to deep feature representations.

---

## 🎯 Objectives

* Extract meaningful **texture features** using statistical methods
* Train and evaluate **classical ML models** (SVM, KNN, Random Forest)
* Build a **custom CNN architecture** for image classification
* Apply **transfer learning** using ResNet50
* Compare performance across all approaches

---

## 📂 Dataset

* **Dataset:** Describable Textures Dataset (DTD)
* Source: Kaggle
* Contains multiple classes of real-world textures

---

## ⚙️ Pipeline

### 1. Data Preprocessing

* Grayscale conversion
* Image resizing (128×128)
* Histogram equalization
* Gaussian filtering
* Normalization

---

### 2. Feature Engineering (Classical Vision)

#### 🔹 GLCM (Gray-Level Co-occurrence Matrix)

Extracted features:

* Contrast
* Dissimilarity
* Homogeneity
* Energy
* Correlation

#### 🔹 LBP (Local Binary Patterns)

* Captures local texture structure
* Histogram-based representation

---

### 3. Classical Machine Learning Models

* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Random Forest

Evaluation:

* Accuracy
* Confusion Matrix

---

### 4. Deep Learning (CNN)

Custom architecture:

* Conv → ReLU → MaxPooling
* Deep feature extraction
* Fully connected classifier

Includes:

* Data augmentation
* Validation tracking

---

### 5. Transfer Learning (ResNet50)

* Pretrained on ImageNet
* Frozen base layers
* Custom classification head

Advantages:

* Faster convergence
* Improved generalization

---

## 📊 Evaluation Metrics

* Accuracy
* Confusion Matrix
* Classification Report (Precision, Recall, F1-score)
* ROC-AUC (optional extension)

---

## 🧪 Results

The project compares:

* Handcrafted features vs Deep features
* Classical ML vs CNN vs Transfer Learning

👉 Typically:

* CNN outperforms classical models
* Transfer learning achieves the **best performance**

---

## 🚀 Technologies Used

* Python
* NumPy, Pandas
* OpenCV
* Scikit-image
* Scikit-learn
* TensorFlow / Keras
* Matplotlib & Seaborn

---

## 📈 Key Insights

* Handcrafted features (GLCM + LBP) are powerful but limited
* CNNs automatically learn hierarchical features
* Transfer learning significantly boosts performance with less training time
* Combining approaches provides a deeper understanding of image representations

---

## 🔮 Future Improvements

* Fine-tune ResNet layers
* Use more advanced architectures (EfficientNet, Vision Transformers)
* Apply feature fusion (combine GLCM + CNN features)
* Hyperparameter optimization
* Cross-validation

---

## 👨‍💻 Author

Developed as part of an AI & Data Science learning project.

---

## ⭐ Final Note

This project demonstrates the evolution of computer vision:

> From **manual feature engineering** → to **automated deep representation learning**

---
