# Facial Emotion Recognition with Real-Time Webcam Pipeline

An end-to-end Deep Learning project designed to classify human facial expressions into distinct emotional states and deploy the trained model through a live, real-time webcam inference pipeline.

---

## 📌 Project Overview
This project leverages computer vision and deep learning techniques to analyze and recognize facial expressions. By processing image data through a Convolutional Neural Network (CNN), the system learns to identify key facial features associated with different emotions (such as Happy, Sad, Angry, Surprise, and Neutral). 

The final pipeline integrates a live webcam feed using OpenCV, allowing the model to perform face detection, crop the face region, and display instantaneous emotion predictions on-screen in real time.

---

## 🛠️ Features
* **Custom CNN Architecture:** Optimized for localized facial feature extraction and pattern recognition.
* **Data Preprocessing & Augmentation:** Built-in pipelines to resize, normalize, and augment training samples to improve generalization.
* **Live Inference Pipeline:** Real-time face tracking and immediate emotion classification via a standard computer webcam.

---

## 💻 Tech Stack & Libraries
* **Language:** Python
* **Deep Learning Framework:** TensorFlow / Keras
* **Computer Vision:** OpenCV (cv2)
* **Data Manipulation & Visualization:** NumPy, Pandas, Matplotlib, Seaborn

---

## 🚀 How It Works
1. **Face Detection:** The live webcam script uses a Haar Cascade classifier to locate faces within each frame of the video feed.
2. **Preprocessing:** The detected face region is cropped, converted to grayscale, and resized to the model's required input dimensions.
3. **Classification:** The preprocessed face image is fed into the trained Convolutional Neural Network.
4. **Display:** The model outputs probability scores, and the highest-scoring emotion label is rendered dynamically above the bounding box around the user's face.

