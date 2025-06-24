Real-Time Fruit Detection and Yield Analysis with YOLOv5
Fruit Detection System using YOLOv5
This project implements a real-time fruit detection system using YOLOv5 (You Only Look Once) object detection algorithm. The goal is to accurately identify and classify different types of fruits from images or video streams. The model was trained on a custom dataset of labeled fruit images.

Features
Trained YOLOv5 model on a custom fruit dataset
Real-time fruit detection from camera/video input
Achieved high accuracy in classifying fruits like apple, banana, and orange
Optimized for performance and small model size
Technologies Used
Python
YOLOv5 (PyTorch-based)
OpenCV for image processing
LabelImg for dataset annotation
Results
Achieved 94% accuracy on test dataset
Detected fruits with over 90% confidence in real-time testing
Dataset included 1200+ labeled images across 3+ fruit classes
How to Run
Clone this repository
Install dependencies: pip install -r requirements.txt
Download the trained weights or train your own using train.py
Run detection: python detect.py --source path_to_image_or_video
