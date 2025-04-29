# 😄 Emotion Detection with CNN & OpenCV

A deep learning-based facial expression recognition system that uses a webcam to detect and classify human emotions in real time using OpenCV and a trained Convolutional Neural Network (CNN).

---

## 🧠 Overview

This project detects faces in a video stream and classifies emotions into one of the seven categories:
- Angry
- Disgust
- Fear
- Happy
- Neutral
- Sad
- Surprise

The model was trained using the **[Face Expression Recognition Dataset](https://www.kaggle.com/jonathanoheix/face-expression-recognition-dataset)** available on Kaggle.

---

## 📁 Project Structure

```bash
DeepLearning/
└── Kunskapskontroll 2/
    ├── Kunskapskontroll 2.ipynb       # Jupyter notebook for model training
    ├── main.py                        # Real-time emotion detection script
    ├── model_file.keras               # Trained CNN model file
    ├── haarcascade_frontalface_default.xml  # Haar cascade for face detection
    ├── history_plot.png               # Training accuracy/loss plot
    └── README.md                      # This file
