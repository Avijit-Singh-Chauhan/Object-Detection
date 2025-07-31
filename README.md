# Object Detection 🚗📸 

## Project Overview
This project, **"Object Detection,"** focuses on building a computer vision system capable of identifying vehicles. It comprises two distinct but complementary codebases: one for image capture and another for vehicle detection.The image capture module is the building block to 
capture visual information, which is input into the vehicle detection module. This second module utilizes object detection algorithms to precisely detect and identify vehicles in the recorded images or video streams, which constitutes the main function of the system. This
combination allows for a flexible framework that can be adapted for various applications such as traffic monitoring, autonomous driving research, or surveillance.

## Features ✨
- **Image Capture Module:**

Acquires images from a specified source (e.g., webcam, local file).  
Add more specific capture features if applicable, e.g., customizable resolution, frame rate.

- **Vehicle Detection Module:**

Detects and localizes vehicles within input images/frames.  
Add more specific detection features if applicable, e.g., vehicle counting, classification of vehicle types like car, bus, truck.

## Prerequisites 📋
- Python 3.6 or higher installed on your system
- OpenCV library installed
- YOLOv4 pre-trained model files (yolov4.cfg, yolov4.weights) available for use
