# Lab 4: Autonomous Driving Application - Car Detection using YOLO

## 📌 Overview
This project implements an **object detection pipeline** using the YOLO (You Only Look Once) model to detect cars in images. The lab demonstrates:
- Loading and using YOLO for object detection.
- Post-processing detections using **Non-Maximum Suppression (NMS)** with TensorFlow.
- Analyzing the effect of **confidence thresholds** on detection performance.
- Visualizing detections and class distributions.

---

## 🛠 Requirements
- Python 3.8+
- Google Colab or Jupyter Notebook
- Packages:
  - `tensorflow`
  - `opencv-python`
  - `matplotlib`
  - `numpy`

Install dependencies (if running locally):
```bash
pip install tensorflow opencv-python matplotlib numpy
