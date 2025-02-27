YOLO Real Time Object Detection
This project implements real-time object detection via video, webcam, and image detection using the YOLO algorithm. YOLO (You Only Look Once) is an object detection algorithm that is efficient and fast. This implementation uses pre-trained weights for YOLOv3 in Python.

Overview:
YOLOv3 is implemented using pre-trained weights for real-time object detection.
COCO dataset is used for training the model.
This project can perform real-time detection via the command prompt or a graphical user interface (GUI).
Demo Images:
A USA Real-Time Road Detection:

A UK Real-Time Road Detection:

Real-Time Webcam Detection:

About YOLO:
YOLO (You Only Look Once) was introduced in 2016 and became quickly popular due to its speed compared to other deep learning algorithms. With a GPU, YOLO can process over 45 frames per second, whereas on a CPU it can process about 1 frame per second. This makes it ideal for real-time object detection applications.

Requirements:
OpenCV 4.2.0
Python 3.6
Quick Start:
Download the official YOLOv3 weights from YOLOv3 weights and place them in a folder called weights.
Download the official YOLOv3-tiny weights from YOLOv3-tiny weights and place them in a folder called weights.
Download the YOLOv3 config file from YOLOv3 config and place it in a folder called cfg.
Download the YOLOv3-tiny config file from YOLOv3-tiny config and place it in a folder called cfg.
Dependencies:
opencv
numpy
Install dependencies:
To install required dependencies, run the following command:

bash
Copy
pip install numpy opencv-python
How to use:
Clone the repository:

bash
Copy
git clone https://github.com/yourusername/YOLO-Real-Time-Object-Detection.git
Navigate to the project directory:

bash
Copy
cd YOLO-Real-Time-Object-Detection
To view the USA Real-Time Road Detection:

bash
Copy
python real_time_yolo_detector1.py
To view the UK Real-Time Road Detection:

bash
Copy
python real_time_yolo_detector2.py
To use real-time webcam detection:

bash
Copy
python real_time_yolo_webcam.py
Graphical User Interface (GUI) Screenshots:
USA Real-Time Road Detection:

UK Real-Time Road Detection:

Real-Time Webcam Detection: