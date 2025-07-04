# 🧠 Emotion Detector - Real-Time Facial Emotion Recognition

This project is a real-time facial emotion detection web app that uses computer vision and deep learning. The goal is to recognize human emotions through facial expressions captured by a webcam, and classify them into predefined emotional categories using a Convolutional Neural Network (CNN).

🔴 **Live App**: [https://emotion-detector-mgv164.onrender.com](https://emotion-detector-mgv164.onrender.com)

---

## 📸 What It Does

- Captures webcam input in real time.
- Detects and isolates faces using OpenCV.
- Uses a trained CNN model to predict emotions.
- Displays the predicted emotion on the screen with the face box.
- Supports multiple emotional states.

---

## 😃 Recognized Emotions

The CNN model is trained to recognize the following 7 basic emotions:

- 😄 Happy
- 😢 Sad
- 😠 Angry
- 😱 Fear
- 😐 Neutral
- 😲 Surprise
- 🤢 Disgust

---

## 🛠️ Technologies Used

- `Python 3.10`
- `Streamlit 1.25.0`
- `TensorFlow 2.10.1`
- `Keras 2.10.0`
- `OpenCV (opencv-python-headless)`
- `NumPy`
- `Matplotlib`
- `Pillow`
- `H5py`

---

## 🧰 Installation (Local)

To run the app locally:

```bash
# Clone the repository
git clone https://github.com/MariluzGayosso/Emotion-Detector.git

# Navigate into the folder
cd Emotion-Detector

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
