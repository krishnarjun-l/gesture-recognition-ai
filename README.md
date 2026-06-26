# Gesture Recognition for Smart TV Home Automation

## 📌 Project Overview
Developed a deep learning-based gesture recognition system that identifies five distinct hand gestures to control a smart TV. The model processes video sequences (sequences of frames) to trigger actions like volume control, play/pause, and navigation.

## 🧠 Approach & Model Selection
Recognizing gestures in video requires capturing both **spatial** (image features) and **temporal** (movement over time) information. I experimented with two primary architectures:
1. **3D Convolutional Neural Networks (3DCNN):** To extract spatial and temporal features simultaneously using 3D filters.
2. **CNN + RNN (Conv2D + LSTM/GRU):** Using a pre-trained CNN to extract features from individual frames and an RNN to analyze the sequence of these features.

## 📊 Dataset
* **Source:** 100+ videos of 5 different gestures (Thumbs up/down, Swipe Left/Right, Stop).
* **Processing:** Images were resized and normalized. Data augmentation techniques like rotation and flipping were applied to ensure model robustness.

## 🛠️ Tech Stack
* **Language:** Python
* **Deep Learning:** TensorFlow, Keras
* **Processing:** NumPy, OpenCV, Scikit-image
* **Optimization:** Used Batch Normalization, Dropout, and various optimizers (SGD, Adam) to prevent overfitting.

## 📂 Repository Structure

...

 ├── CaseStudy_GestureRecognition.ipynb
 ├── write-up_gesture_recognization.docx
 ├── requirements.txt
 └── README.md
...
