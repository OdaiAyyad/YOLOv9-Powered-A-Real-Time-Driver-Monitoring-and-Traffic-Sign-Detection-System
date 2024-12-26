# YOLOv9-Powered-A-Real-Time-Driver-Monitoring-and-Traffic-Sign-Detection-System 🚦🚗

Overview

This project showcases the development of a Traffic Safety System, leveraging the YOLOv9 model for advanced object detection. The system integrates two datasets to detect traffic signs and monitor driver behaviors, providing real-time feedback via voice alerts.

Features

1️⃣ Dual Dataset Integration:

Driver Monitoring Dataset: Tracks behaviors like drowsiness, phone usage, and seatbelt compliance.

Traffic Sign Dataset: Recognizes road signs such as speed limits and stop signs.


2️⃣ YOLOv9 vs. YOLOv8 Comparison:

Conducted an in-depth analysis of speed, accuracy, and computational requirements between YOLOv9 and YOLOv8.


3️⃣ Local Real-Time Implementation:

The system utilized local hardware for real-time demonstrations, enabling access to webcams and showcasing its capabilities during our graduation presentation.


4️⃣ Google Colab Pro Utilization:

Due to YOLOv9's intensive training demands (large parameters and high computational requirements), we used Google Colab Pro with TPU support. This significantly reduced training time and ensured smooth execution.


Results

🎯 Accurate Detection: Achieved high accuracy across both datasets.

⚡ Real-Time Performance: Successfully demonstrated object detection live.

🔊 Voice Feedback: Enhanced user experience with text-to-speech alerts.


Getting Started

1. Clone this repository.


2. Prepare your datasets in YOLO format.


3. Train the model using the provided scripts (train.py) on Google Colab Pro or another training platform.


4. Test and run real-time detection using real_time_detection.py on local hardware.



Acknowledgements

Special thanks to our supervisors and teammates who contributed to this amazing journey. 🎓

Feel free to explore the repository and reach out for any questions or feedback! 🚀
