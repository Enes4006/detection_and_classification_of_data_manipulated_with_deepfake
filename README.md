# 🎭 Deepfake Video Detection with Deep Learning

This project focuses on detecting deepfake videos using deep learning techniques. It serves as a foundational implementation for a more advanced system that will incorporate state-of-the-art architectures such as EfficientNet and ResNet.

---

## 📌 Project Overview

With the rapid advancement of AI-generated media, detecting manipulated videos has become a critical problem. This project aims to classify videos as **REAL or FAKE** using a CNN-based pipeline.

This project represents an initial step toward building a robust deepfake detection system. While current results are limited, the architecture is scalable and ready for advanced enhancements.

---

## 🧠 Current Pipeline

The implemented system follows this workflow:

Video → Frame Extraction → Preprocessing → Data Augmentation → CNN Model → Prediction

### 🔹 Key Steps:
- 🎥 Video frame extraction using OpenCV
- 🖼️ Image preprocessing (resize + normalization)
- 🔁 Data augmentation:
  - Horizontal Flip
  - Rotation
  - Zoom
- 🧠 CNN-based classification model
- 📊 Model evaluation using accuracy and classification report

---

## ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

---

## 📊 Model Performance

Although the system is functional, performance is currently limited due to dataset size.

> The applied L2 Regularization and Dropout techniques successfully reduced overfitting (see Loss Graph). However, the dataset size (10 videos) is insufficient for the model to generalize deepfake patterns effectively. Increasing dataset size (e.g., 100+ videos) is expected to significantly improve performance.

---

## ⚠️ Challenges Faced

- Limited dataset size (only 10 videos)
- High risk of overfitting
- Difficulty in generalizing deepfake features
- Computational limitations during frame extraction
- Noise and irrelevant frames in videos

---

## ✅ Improvements Implemented

- ✔ Data augmentation (flip, rotation, zoom)
- ✔ Dropout for regularization
- ✔ Early Stopping to prevent overfitting
- ✔ Batch Normalization for stable training

---

## 🚀 Future Work

This project is designed as a **baseline system**. Future improvements include:

- 🔥 Transfer Learning:
  - EfficientNet
  - ResNet
- 😐 Face Detection & Face Cropping (MTCNN / Haar Cascade)
- 🎥 Temporal modeling using LSTM
- 📊 Larger datasets:
  - FaceForensics++
  - DFDC
- ⚡ Performance optimization & hyperparameter tuning


---

## 🕵️ Deepfake Detection & Classification System (Phase 1)

This repository contains the **first phase** of a Deepfake detection system developed as part of the *Computer Engineering Design Course* at Yozgat Bozok University.

### 🛠 What Has Been Done So Far?

- **Pipeline Development:**  
  An end-to-end workflow has been designed, including:
  - Video to frame extraction  
  - Face detection (planned / partially implemented)  
  - Image normalization  

- **Overfitting Mitigation:**  
  Due to the small dataset size, overfitting was a major challenge. This was addressed using:
  - Dropout layers  
  - Early Stopping  
  - Batch Normalization  

- **Data Augmentation:**  
  Dataset diversity was increased using:
  - Flip  
  - Rotation  
  - Zoom  

<img width="1310" height="317" alt="Ekran görüntüsü 2026-03-29 165839" src="https://github.com/user-attachments/assets/0cd0c2f9-37d3-481b-8090-277fdf912b78" />
<br>
<img width="869" height="580" alt="Ekran görüntüsü 2026-03-29 165800" src="https://github.com/user-attachments/assets/679d8a73-a67f-4b91-8adb-1023d1b3029c" />
<br>
<img width="1298" height="535" alt="Ekran görüntüsü 2026-03-29 160734" src="https://github.com/user-attachments/assets/b7ae3d9d-9061-4fb4-9063-e2f6a48fdfeb" />



