# Car Detection with YOLO

Vehicle detection in images and video using the YOLO object detection model.

## Overview

This project uses a YOLO model to locate cars (and other vehicles) in images, video files or a live camera stream, drawing bounding boxes with class labels and confidence scores.

## Tech Stack

- Python
- [Ultralytics YOLO](https://github.com/ultralytics/ultralytics)
- OpenCV

## Getting Started

```bash
pip install ultralytics opencv-python
```

Run detection on an image or video:

```bash
yolo predict model=yolov8n.pt source=path/to/image_or_video.mp4 classes=2
```

(`classes=2` keeps only the COCO `car` class; remove it to detect all objects.)

## Results

_Add sample output images or a GIF here._

## Roadmap

- [ ] Upload detection script / notebook
- [ ] Add sample results
- [ ] Fine-tune on a custom vehicle dataset
- [ ] Vehicle counting and tracking
