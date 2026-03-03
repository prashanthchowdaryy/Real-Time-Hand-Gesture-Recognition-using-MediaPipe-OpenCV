Real-Time Hand Gesture Recognition using MediaPipe & OpenCV
📌 Overview

This project implements real-time hand gesture detection using MediaPipe and OpenCV in Python.

The system detects hand landmarks through a webcam feed and tracks finger movements in real time. It can be extended for gesture-based control systems, virtual mouse, sign recognition, or AI-based interaction systems.

Built as part of practical exploration in Computer Vision and AI.

🚀 Features

✅ Real-time hand tracking

✅ 21 hand landmark detection

✅ Finger state detection (open/closed)

✅ Live webcam integration

✅ High accuracy using MediaPipe ML models

✅ Lightweight & fast execution

🛠️ Tech Stack

Python

OpenCV

MediaPipe

NumPy

📂 Project Structure
mediapipe-hand-gesture/
│
├── hand_tracking.py
├── requirements.txt
├── README.md
└── screenshots/
⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/your-username/mediapipe-hand-gesture.git
cd mediapipe-hand-gesture
2️⃣ Install Dependencies
pip install -r requirements.txt

Or manually install:

pip install opencv-python mediapipe numpy
▶️ How to Run
python hand_tracking.py

Your webcam will start, and hand landmarks will be detected in real time.

Press Q to exit.

🧠 How It Works

MediaPipe uses a pre-trained ML model to detect 21 hand landmarks.

OpenCV captures live video frames.

Each frame is processed and annotated with landmark positions.

Finger states are determined by comparing landmark coordinates.

The output is displayed in real-time.

📸 Demo

(Add screenshots or demo GIF here)

Example output:

Hand landmark detection

Finger tracking visualization

Real-time FPS counter

📈 Applications

Virtual Mouse

Gesture-Based Volume Control

Sign Language Recognition

AR/VR Interaction

Gaming Controls

Touchless Interfaces

🔮 Future Improvements

Gesture classification model

Custom gesture training

Integration with system controls

GUI dashboard

Deployment as desktop application

📚 Learning Outcomes

Practical use of MediaPipe ML solutions

Real-time computer vision pipeline

Frame processing optimization

Coordinate-based logic building

AI model integration in applications

👨‍💻 Author

Prashanth
BCA Student | Aspiring Data Scientist
Passionate about AI, Automation & Real-World Problem Solving

⭐ If You Like This Project

Give it a star 🌟
Contributions and suggestions are welcome!
