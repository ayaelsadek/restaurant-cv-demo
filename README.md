# Restaurant CV Demo 🎥

A real-time people detection pipeline built with YOLOv8 and OpenCV,
simulating a restaurant operations camera analytics system.

## What It Does
- Reads a video stream (simulating an RTSP camera feed)
- Detects and counts people per frame using YOLOv8n
- Overlays live people count on the output video
- Saves annotated output for review

## Demo Output
![Sample Output](sample_output.png)

## Tech Stack
- Python 3.x
- OpenCV
- Ultralytics YOLOv8
- Google Colab (development environment)

## How to Run

### Install dependencies
pip install ultralytics opencv-python

### Run
python demo.py

## Project Context
This demo is part of my exploration of edge AI pipelines for
restaurant operations systems, targeting deployment on devices
like NVIDIA Jetson Orin Nano with TensorRT-optimized inference
and RTSP camera stream ingestion.

## Author
Aya Elsadek
github.com/ayaelsadek
linkedin.com/in/aya-elsadek-b4080a164
