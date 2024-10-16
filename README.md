# Real-time-Object-Detection-with-YOLO
There are certain limitations in commonly used object detection approaches, due to which, it is often necessary to sacrifice accuracy in order to ensure the infer speed of the detector that is in practice. Therefore, it is important to achieve the balance between effectiveness and efficiency of object detector. The aim of this project is to implement an object detector with relatively balanced effectiveness as well as efficiency that can be directly applied in practical scenarios, rather than propose a novel detection model and develop a real-time object detection model based on YOLO-V3  network to solve the underlying problems with existing methods and incorporate fast and improved detection.


# Objective:
The goal was to develop a real-time object detection model using the YOLO-V3 network to address the challenges in classical object detection methods. The primary focus was on enhancing speed and accuracy for detecting objects in videos, live feeds, or images, suitable for practical applications like surveillance and autonomous systems.

# Framework:
Darknet (YOLO-V3's neural network framework)

# Libraries & Tools:
OpenCV (for image processing and real-time video stream handling)
Python (programming language for implementation)

# Development Environment:
Visual Studio Code (VS Code) for development and debugging
Jupyter Notebook for model training and evaluation

# Techniques Used:
Convolutional Neural Networks (CNNs) for object detection and classification
Bounding Box Regression for object localization
Non-Maximum Suppression for reducing duplicate bounding boxes
Intersection over Union (IoU) to measure accuracy of object detection

# Datasets:
Trained on the COCO Dataset, capable of detecting 80 object classes
Implemented custom datasets for specialized object detection use cases

# Model Architecture:
YOLO-V3 architecture uses Darknet-53 as a backbone, with a total of 106 convolutional layers, enabling fast detection without sacrificing accuracy.
Object detection is performed at three different scales, addressing issues of detecting small objects through a multi-scale approach.

# Performance:
Achieved real-time detection with high accuracy and minimal delay, ensuring suitability for live video streams.
Detected multiple objects per frame with robust precision, even for smaller and overlapping objects.

# Applications:
Surveillance Systems for monitoring and threat detection
Autonomous Vehicles for real-time obstacle detection
Robotics for identifying and manipulating objects in dynamic environments

# Key Accomplishments:
Successfully implemented a real-time object detection system using YOLO-V3, balancing both speed and accuracy in dynamic environments.
Tackled challenges like object overlap, scale variation, and background noise, demonstrating efficient detection in live video feeds.
