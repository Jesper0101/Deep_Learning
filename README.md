# Emotion Detection with CNN & OpenCV

A deep learning-based facial expression recognition system that uses a webcam to detect and classify human emotions in real time using OpenCV and a trained Convolutional Neural Network (CNN).

---

## Overview

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

## Project Structure

```bash
DeepLearning/
└── Kunskapskontroll 2/
    ├── Kunskapskontroll 2.ipynb         # Jupyter notebook for model training
    ├── main.py                          # Real-time emotion detection script
    ├── model_file.keras                 # Trained CNN model file
    ├── haarcascade_frontalface_default.xml  # Haar cascade for face detection
    ├── history_plot.png                 # Training accuracy/loss plot
    └── README.md                        # This file
```

# Getting Started
Requirements
Install the necessary dependencies:

pip install tensorflow keras opencv-python numpy matplotlib pandas seaborn
Running Emotion Detection (Live Webcam)
Make sure your webcam is connected and run:

python main.py
Press Q to exit the live window.

Detected faces will be outlined, and emotions displayed in real-time.

# Model Training (Optional)
The CNN was trained using grayscale images (48x48) from the FER dataset. The notebook Kunskapskontroll 2.ipynb contains:

# Data preprocessing

Image generators for training/validation

CNN architecture with Conv2D, BatchNorm, ReLU, MaxPooling, and Dropout

Model training with callbacks: EarlyStopping, ModelCheckpoint, ReduceLROnPlateau

Accuracy & loss visualization (history_plot.png)

Note: To train the model yourself, download the dataset from Kaggle and place it appropriately, updating paths in the notebook.

# Training Results
Model achieved ~49% validation accuracy across 7 emotion classes.



# Why Emotion Detection?
Facial emotion recognition can be used in:

Human-computer interaction

Smart surveillance

Mental health monitoring

Customer feedback systems

Education technology

# License
This project is for educational use.

# Acknowledgments
Face Expression Recognition Dataset – Kaggle

TensorFlow / Keras

OpenCV for face detection
