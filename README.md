# Animal Detection and Carnivore Identification System using YOLOv8
Overview:

This project uses the YOLOv8 deep learning model to detect animals in images and videos. It highlights carnivorous animals in red and counts them separately.

This system can be used in wildlife monitoring, surveillance, and smart detection systems.

# Features

Detect animals in images and videos

Highlight carnivorous animals in red

Count carnivorous animals

Real-time detection support

Uses YOLOv8 object detection model

# Technologies Used

Python

YOLOv8 (Ultralytics)

OpenCV

Pandas

Matplotlib

# Deep Learning Model

Model Used: YOLOv8 (You Only Look Once)

Capabilities:

Real-time object detection

High accuracy

Fast processing speed

# Carnivores Detected

The system detects:

Lion

Tiger

Bear

Wolf

Leopard

Dog

Cat

Fox

# Project Structure
Animal-Detection-System/

│
├── dataset2_labels.csv
├── yolov8n.pt
├── animal_detection.py
├── sample_video.mp4
├── README.md
└── requirements.txt

# Installation
pip install ultralytics opencv-python pandas matplotlib
Run the Project
python animal_detection.py

# Example Output

Image Detection:

Carnivores detected: 2

Video Detection:

Total carnivores detected: 15
# How It Works

Step 1: Load YOLOv8 model
Step 2: Load image or video
Step 3: Detect animals
Step 4: Classify carnivores
Step 5: Draw bounding boxes
Step 6: Count carnivores

# Applications

Wildlife monitoring

Forest surveillance

Animal research

Smart surveillance systems

AI-based detection systems

# Model Performance

Real-time detection speed

High accuracy object detection

Supports multiple animals per frame

# Future Improvements

Custom-trained animal detection model

Real-time webcam detection

Alarm system for carnivore detection

Web application integration
