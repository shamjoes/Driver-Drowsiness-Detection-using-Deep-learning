# Driver Drowsiness & Yawn Detection System

A real-time deep learning driver-monitoring system that tracks facial landmarks, eye aspect ratio (EAR), and yawn frequency to identify early stages of driver fatigue and microsleep, sounding an immediate alarm.

## Features
- **Eye Aspect Ratio (EAR) Monitoring**: Detects prolonged eye closure indicative of drowsiness.
- **Yawn Detection**: Monitors mouth aspect ratio to catch early fatigue indicators.
- **Facial Emotion Recognition**: Secondary CNN model evaluating facial strain.
- **Acoustic Warning Alarm**: Triggers audio warnings when danger thresholds are breached.

## Quickstart

`ash
git clone https://github.com/shamjoes/Driver-Drowsiness-Detection-using-Deep-learning.git
cd Driver-Drowsiness-Detection-using-Deep-learning

pip install -r requirements.txt
python "Source code/detect_drowsiness.py"
`

## Tech Stack
- Python 3.8+
- TensorFlow / Keras
- OpenCV
- SciPy & NumPy
- Pygame (Audio Alarm)