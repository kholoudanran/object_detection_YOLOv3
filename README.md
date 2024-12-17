# Object Detection with YOLOv3 using OpenCV

This project demonstrates how to perform object detection using YOLOv3 (You Only Look Once) with OpenCV.

# Setup
Clone the repository or download the necessary files to your local machine.
Ensure you have Python installed on your system.

Install the required libraries by running:
pip install opencv-python numpy

Download the YOLOv3 weights and configuration file from the official YOLO website.
Download the coco.names file containing class names from the COCO dataset.

# Usage
Navigate to the project directory:
cd path/to/project

Update the file paths in the script to match the location of your YOLOv3 files and the image you want to perform object detection on.

Run the script:
python object_detection_yolov3.py

# Description
The script loads the YOLOv3 model with the pre-trained weights and configuration.
It reads the class names from the coco.names file.
An image (test_img.jpg) is loaded, resized, and processed for object detection.
Detected objects are drawn as bounding boxes on the image.
The result is saved as result.jpg and displayed using OpenCV.

# References
YOLO: Real-Time Object Detection
COCO Dataset
