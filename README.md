# Automatic Train Coach Detection and Counting with YOLOv8

## Overview
This project implements an **end-to-end computer vision pipeline** to automatically detect and count train coaches and engines from side-view videos. Using **YOLOv8**, **DeepSORT**, and **OpenCV**, it generates per-coach video clips and representative frames while tracking each coach to avoid duplicate counts. The model is fine-tuned on a **custom dataset of ~650 annotated images**.

## Key Features
- Fine-tuned YOLOv8 for accurate coach and engine detection.
- Implemented **object tracking (DeepSORT)** to eliminate duplicate counts.
- Generated **per-coach video clips** and **representative frames** covering each coach from nose to tail.
- Validated on multiple real train-passing videos.

## Technologies
- **Languages:** Python
- **Libraries:** OpenCV, YOLOv8 (Ultralytics), DeepSORT, NumPy, Pandas
- **Environment:** Google Colab / Jupyter Notebook


