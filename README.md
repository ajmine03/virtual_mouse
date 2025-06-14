# 🖱️ Virtual Mouse using Hand Tracking

This is a Python project that turns your hand into a virtual mouse using your webcam. It uses **OpenCV**, **MediaPipe**, and **PyAutoGUI** to detect hand gestures and control the mouse on your screen.

## 📸 Features

- Move the mouse cursor using your index finger
- Left-click by bringing your thumb close to your index finger
- Real-time webcam input
- Smooth and intuitive gesture control

## 🚀 How It Works

- The program captures video frames from your webcam.
- MediaPipe detects the hand landmarks in each frame.
- The index finger controls the mouse cursor.
- A click is performed when the index and thumb fingers come close together.

## 🛠️ Requirements

Make sure you have Python 3.7+ installed.

Install the required Python packages:

```bash
pip install opencv-python mediapipe pyautogui
