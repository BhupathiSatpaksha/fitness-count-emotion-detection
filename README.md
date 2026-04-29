# fitness-count-emotion-detection
AI-based system for real-time fitness tracking and emotion detection using computer vision and deep learning.


## 📌 Overview

This project combines **Computer Vision** and **Deep Learning** to create a real-time system that:

* Detects human emotions from facial expressions
* Tracks body movements using pose estimation
* Counts exercise repetitions (e.g., push-ups)
* Provides live visual feedback

---

## 🚀 Features

* 🎭 Real-time Emotion Detection (CNN Model)
* 🏋️ Fitness Exercise Counter (Push-up detection)
* 🧍 Pose Detection using MediaPipe
* 🙂 Face Detection using Haar Cascade
* 📷 Live Webcam Processing

---

## 🧠 Tech Stack

* Python
* OpenCV
* MediaPipe
* TensorFlow / Keras
* NumPy
* Matplotlib

---

## 📂 Project Structure

```
📁 fitness-count-emotion-detection
│
├── TrainEmotionDetector.py        # Model training script
├── EvaluateEmotionDetector.py     # Model evaluation
├── mini.py                        # Pose detection (fitness counter)
├── mini2.py                       # Combined system (emotion + fitness)
├── emotion_model.json             # Model architecture
├── emotion_model.h5               # Trained model weights
├── haarcascade_frontalface_default.xml  # Face detection
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/BhupathiSatpaksha/fitness-count-emotion-detection.git
cd fitness-count-emotion-detection
```

### 2️⃣ Install Dependencies

```bash
pip install opencv-python mediapipe tensorflow keras numpy matplotlib
```

---

## ▶️ How to Run

### Run Full System (Recommended)

```bash
python mini2.py
```

### Run Only Fitness Counter

```bash
python mini.py
```

### Train Model (Optional)

```bash
python TrainEmotionDetector.py
```

### Evaluate Model

```bash
python EvaluateEmotionDetector.py
```

---

## ⚠️ Requirements

* Webcam (for real-time detection)
* Python 3.x
* Required libraries installed

---

## 📊 Model Details

* CNN-based architecture for emotion classification
* Trained on grayscale facial images (48x48)
* Detects 7 emotions:

  * Angry
  * Disgusted
  * Fearful
  * Happy
  * Neutral
  * Sad
  * Surprised

---

## ⚠️ Limitations

* Dataset not included (large size)
* Requires good lighting for accurate detection
* Accuracy may vary based on environment

---

## 🎯 Future Improvements

* Add GUI dashboard (React / Streamlit)
* Improve model accuracy with larger dataset
* Add more exercises (squats, jumping jacks)
* Deploy as a web application

---


## 👨‍💻 Author

Bhupathi Satpaksha

---

## ⭐ Acknowledgements

* OpenCV
* MediaPipe
* TensorFlow / Keras
