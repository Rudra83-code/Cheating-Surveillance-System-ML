📌 Overview

The Cheating Surveillance System is an AI-driven monitoring solution developed to detect suspicious behavior during online interviews and examinations. The system analyzes head movement, eye gaze direction, and unauthorized mobile phone usage in real time using computer vision and deep learning techniques.

It integrates facial landmark detection using dlib’s 68-point shape predictor with YOLO-based object detection trained on a mobile phone dataset from Roboflow.

🚀 Key Features
1️⃣ Head Pose & Eye Movement Analysis

Tracks 68 facial landmarks using dlib

Detects gaze direction (left, right, upward, downward)

Identifies abnormal or excessive head and eye movement patterns

2️⃣ Mobile Phone Detection

YOLOv8 / YOLOv12 object detection model

Trained on a custom cellphone detection dataset

Detects unauthorized mobile devices in real time

3️⃣ Real-Time Monitoring

Processes live webcam feed using OpenCV

Performs frame-by-frame behavioral analysis

4️⃣ Automated Alert Mechanism

Flags suspicious head or eye movement beyond a defined threshold

Detects presence of mobile phones during monitoring sessions

🛠️ Technologies Used

Python

OpenCV

dlib

PyTorch

YOLO (You Only Look Once)

Roboflow Dataset



cheating-surveillance/
│── models/
│   ├── best_yolov8.pt
│   ├── best_yolov12.pt
│   ├── shape_predictor_68_face_landmarks.dat
│
│── log/
│
│── main.py
│── head_pose.py
│── eye_movement.py
│── mobile_detection.py
│── requirements.txt
│── README.md


⚙️ Installation
Prerequisites

Python 3.8 – 3.10 (Recommended)

pip

Webcam
