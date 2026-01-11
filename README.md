# Hand Gesture Recognition using MediaPipe & Machine Learning

This project implements a **real-time hand gesture recognition system** using **Computer Vision and Machine Learning**.  
The system detects hand landmarks using the **MediaPipe Tasks API** and classifies gestures using a **Support Vector Machine (SVM)** model.

The project was developed as part of a **Machine Learning Internship task**.

---

## 🚀 Features
- Real-time hand gesture recognition using webcam
- MediaPipe Tasks API for accurate 3D hand landmark extraction
- Machine Learning–based gesture classification (SVM)
- High accuracy (~99%)
- End-to-end pipeline: data processing → training → evaluation → real-time inference

---

## 🧠 Gestures Supported
The model recognizes the following 10 hand gestures:
- Palm  
- L  
- Fist  
- Fist Moved  
- Thumb  
- Index  
- OK  
- Palm Moved  
- C  
- Down  

---

## 🛠️ Tech Stack
- **Python**
- **OpenCV**
- **MediaPipe Tasks API**
- **Scikit-learn**
- **NumPy**
- **Matplotlib**

---

## 📊 Model Performance
- Accuracy: **~99.96%**
- Evaluated using:
  - Classification Report
  - Confusion Matrix
  - Class-wise Accuracy Plots

The results show near-perfect precision and recall across all gesture classes.
