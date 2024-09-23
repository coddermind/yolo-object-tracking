# yolo-object-tracking
This repository contains a project that integrates YOLOv8 from Ultralytics with OpenCV for real-time object tracking and detection. The project allows you to run the YOLOv8 model on a video file or a live camera feed, tracking objects frame by frame and visualizing the results with annotations.
YOLOv8 Object Tracking with OpenCV
This project uses the YOLOv8 object detection model from Ultralytics along with OpenCV for video capture and live object tracking. You can either provide a video file path or use a live camera feed for real-time object detection.

Features
YOLOv8 object tracking
Live camera or video file feed
Object annotation on video frames
Easy-to-use and customizable
Requirements
Before running this project, ensure you have the following dependencies installed:

Python 3.x
OpenCV
Ultralytics YOLOv8
To install the required packages, run the following:

bash
Copy code
pip install ultralytics opencv-python
Setup and Usage
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/yolo-object-tracking.git
Navigate to the project directory:

bash
Copy code
cd yolo-object-tracking
Add your video file to the project directory or use a live camera feed.

Run the project:

bash
Copy code
python yolo_tracking.py
