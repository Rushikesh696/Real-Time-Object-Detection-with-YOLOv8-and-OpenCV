#  Real-Time Object Detection with YOLOv8 and OpenCV

This project demonstrates **real-time object detection** using the YOLOv8 Nano model (`yolov8n.pt`) and a webcam feed. It leverages the **Ultralytics YOLOv8 library** for fast, accurate detection and **OpenCV** for video streaming and visualization.

### Features

✅ Real-time object detection from webcam  
✅ Uses YOLOv8 Nano (pre-trained on COCO dataset)  
✅ Displays bounding boxes, labels, and confidence scores  
✅ Simple and beginner-friendly Python code 

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
