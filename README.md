# 😄 Emotion Detection with CNN & OpenCV

A deep learning project that detects human facial expressions in real-time using a Convolutional Neural Network (CNN), OpenCV for face detection, and TensorFlow/Keras for emotion classification.

---

## 📸 Live Emotion Detection

Using your webcam, this project classifies facial expressions into one of the seven emotions:
- Angry
- Disgust
- Fear
- Happy
- Neutral
- Sad
- Surprise

---

## 🧠 How It Works

- **Face Detection**: Uses OpenCV's Haar Cascade Classifier to detect faces in video frames.
- **Emotion Classification**: A custom-trained CNN model predicts emotions based on facial features.
- **Real-Time Display**: Detected emotions are shown directly on the video feed.

---

## 📁 Project Structure

```bash
DeepLearning/
│
├── main.py                   # Real-time webcam emotion detection
├── model_file.keras          # Trained CNN model
├── haarcascade_frontalface_default.xml  # Haar cascade for face detection
├── images/                   # Dataset with 7 emotion folders
│   └── train/                # Training images by emotion
│   └── validation/           # Validation images by emotion
└── training_notebook.ipynb   # (Optional) Training logic if separated into notebook
