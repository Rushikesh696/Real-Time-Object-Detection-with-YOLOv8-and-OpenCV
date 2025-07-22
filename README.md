#  Real-Time Object Detection with YOLOv8 and OpenCV

This project demonstrates **real-time object detection** using the YOLOv8 Nano model (`yolov8n.pt`) and a webcam feed. It leverages the **Ultralytics YOLOv8 library** for fast, accurate detection and **OpenCV** for video streaming and visualization.

### Features

Real-time object detection from webcam  
Uses YOLOv8 Nano (pre-trained on COCO dataset)  
Displays bounding boxes, labels, and confidence scores  
Simple and beginner-friendly Python code 

### Acknowledgements
Ultralytics YOLOv8

OpenCV

Flask

### What is YOLOv8 Nano (pre-trained on COCO dataset)?
1. **YOLOv8**

YOLO stands for You Only Look Once, which is a real-time object detection algorithm.

YOLOv8 is the latest and most optimized version created by Ultralytics.

It is faster, more accurate, and supports multiple tasks:

Object Detection

Image Segmentation

Pose Estimation

Classification

2. **Nano Version (yolov8n.pt)**

YOLOv8 comes in different sizes:

yolov8n.pt → Nano (lightweight & fast for edge devices)

yolov8s.pt → Small

yolov8m.pt → Medium

yolov8l.pt → Large

yolov8x.pt → Extra Large

Nano is the smallest model. It’s optimized for:

Speed: Works smoothly on CPU and low-end devices.

Low memory usage: Only ~6 MB in size.

Slightly less accurate than larger models, but ideal for real-time webcam applications.

3. **Pre-trained on COCO Dataset**

The Nano model comes pre-trained on COCO (Common Objects in Context).

COCO dataset:

A huge dataset with 80 object classes like person, car, dog, chair, etc.

Used to train many modern object detection algorithms.

In simple terms:
The yolov8n.pt file is a ready-to-use model that already knows how to detect 80 common objects, so you don’t need to train it yourself.

### How YOLOv8 Works

YOLO (*You Only Look Once*) detects objects in a single pass through the neural network.  
It divides the input image into grids and predicts bounding boxes & class probabilities for each grid cell.

Here’s how the detection happens:  
1. **Input Frame:** The webcam captures a frame.  
2. **YOLO Inference:** The frame is passed through YOLOv8 which predicts bounding boxes, classes, and confidence scores.  
3. **Draw Results:** Bounding boxes and labels are drawn using OpenCV.  
4. **Display:** The processed frame is shown in real time.

This project uses `yolov8n.pt`, which is small and optimized for speed.

### What You’ll Learn from This Project

How to use **Ultralytics YOLOv8** for object detection  
How to integrate **OpenCV** with YOLO models for real-time detection  
Drawing bounding boxes and labels on a video feed  
Running lightweight models on CPU for live applications  
Building a beginner-friendly AI project end-to-end

### Next Steps / Challenges for You

Want to take this project further? Try these:  

Replace YOLOv8 Nano (`yolov8n.pt`) with YOLOv8 Small or Medium for better accuracy.  
Use a **custom dataset** and train your own YOLOv8 model.  
Add **object tracking** to follow detected objects across frames.  
Save the webcam feed with detected objects to a video file.  
Deploy this project as a **desktop app** or **web app** using Streamlit or Flask.
