# yolov1-mnist-detection
 YOLOv1 object detection implemented from scratch in PyTorch for MNIST digit detection. Compares 24-layer, 16-layer, and Fast YOLO 9-layer architectures. Visibility: Public
# YOLOv1 Object Detection from Scratch

Implementation of YOLOv1 from scratch in PyTorch for MNIST digit detection.

## Overview
Replicates the original YOLO architecture and compares three variants:
- 24-layer YOLOv1
- 16-layer YOLOv1
- Fast YOLO (9-layer)

## Key Result
Fast YOLO 9-layer achieved ~86% mAP on 16K synthetic MNIST detection scenes.

## Files
- `yolover1-Replication.ipynb` — full implementation and experiments
- `24l8003_YoloProjReport.pdf` — detailed report with architecture diagrams and ablation results

## Tech Stack
Python, PyTorch, NumPy, Matplotlib
