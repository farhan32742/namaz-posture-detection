# Namaz Posture Detection Project

## Overview
This project implements a Namaz (Islamic prayer) posture detection system using the YOLOv8 Nano model. The goal is to identify and classify different prayer postures to assist in learning or analyzing Namaz practices. The project leverages computer vision techniques and deep learning to achieve accurate posture classification.

## Features
- Detects and classifies key Namaz postures such as **Qiyam (Standing)**, **Ruku (Bowing)**, **Sujud (Prostration)**, and **Tashahhud (Sitting)**.
- Lightweight YOLOv8 Nano model optimized for real-time performance.
- Works with both live video streams and pre-recorded videos.
- Outputs annotated frames with detected postures.
- Generates detailed logs of posture occurrences and timestamps.

## Requirements
To run this project, you need the following:

### Software Dependencies
- Python 3.8+
- Required Python libraries:
  ```bash
  pip install ultralytics opencv-python-headless matplotlib
  ```
- Any deep learning framework supported by YOLOv8 (PyTorch recommended).

### Hardware Requirements
- GPU (optional but recommended for faster inference).
- A camera or video input source.

## Model
The YOLOv8 Nano model (`yolov8n`) is used for its efficiency and ability to run on devices with low computational power. The model is trained on a custom dataset containing labeled images of different Namaz postures.

## Dataset
The dataset consists of:
- Images of people performing Namaz in various postures.
- Annotations in YOLO format.

## Setup

### 1. Clone the Repository
```bash
git clone https://github.com/farhan32742/namaz-posture-detection.git
cd namaz-posture-detection
```

### 2. Download the Model
Place your trained YOLOv8 model weights (`best.pt`) in the `models` directory.

### 4. Output
- Annotated video saved in the `outputs/` directory.

## Usage
This project can be used in:
- Learning and teaching Namaz postures.
- Building prayer-related applications.
- Gesture recognition research.

## Challenges
- Dataset diversity and ensuring proper posture alignment.
- Handling varying lighting conditions and camera angles.

## Future Work
- Extend the model to detect incorrect postures and provide feedback.
- Integrate the system into a mobile app for broader accessibility.
- Improve the dataset for better generalization.

## Contact
For any queries or contributions:
- **Name**: Farhan Fayaz
- **Email**: farhanfayaz1987@gmail.com


