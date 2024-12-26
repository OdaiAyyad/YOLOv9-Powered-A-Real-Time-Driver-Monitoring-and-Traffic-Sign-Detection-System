# YOLOv9-Powered-A-Real-Time-Driver-Monitoring-and-Traffic-Sign-Detection-System

Overview

This project introduces a Real-Time Driver Monitoring and Traffic Sign Detection System, leveraging the state-of-the-art YOLOv9 object detection model. Designed to improve road safety, the system integrates real-time alerts via Text-to-Speech (TTS), making it both practical and innovative.

Features

Dual Dataset Integration

Driver Monitoring Dataset:

9,884 images for detecting driver behaviors (e.g., drowsiness, phone usage, seatbelt compliance).


Traffic Sign Dataset:

4,977 images for recognizing road signs (e.g., speed limits, stop signs).



YOLOv9 vs. YOLOv8 Comparison

Models: YOLOv9 and YOLOv8 were compared for speed, accuracy, and efficiency.

Insights: YOLOv9 excelled in scenarios requiring detailed and complex detections.


Real-Time Capabilities

Live Testing: The system was showcased in real-time during our presentation, detecting objects and providing voice alerts instantly.


Text-to-Speech Integration

Alerts drivers with real-time audio notifications, enhancing situational awareness.


Google Colab Pro

The computational intensity of YOLOv9 necessitated Google Colab Pro, ensuring smooth training and execution.


Getting Started

Prerequisites

Google Colab Pro

Python 3.10

Libraries: Ultralytics YOLO, Pyttsx3


Setup

1. Clone this repository.


2. Load the datasets in YOLO format.


3. Run the train.py script for model training.


4. Use the real_time_detection.py script for real-time performance.



Results

The system achieved impressive results in both datasets with high precision and recall, making it a robust tool for traffic safety applications.

Acknowledgements

Special thanks to our supervisors, mentors, and families for their unwavering support.
