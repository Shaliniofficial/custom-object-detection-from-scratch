🧠 Custom Object Detection with Model Training from Scratch
📌 Assignment Overview

This repository contains Assignment 1 for the AI Vision Intern role.
The objective of this assignment is to design, train, and evaluate a custom object detection model from scratch, without using any pre-trained weights, and to demonstrate a complete end-to-end computer vision pipeline.

🎯 Problem Statement

Object detection is a fundamental computer vision task that involves identifying objects within an image and localizing them using bounding boxes.
In this assignment, a complete object detection system is implemented from scratch, covering all stages including dataset preparation, model architecture design, training, evaluation, and inference visualization.

🗂️ Dataset Description

The dataset consists of annotated images containing multiple object classes

Each object is labeled with bounding box coordinates and class labels

Dataset preprocessing steps include:

Image resizing to fixed input dimensions

Pixel normalization to ensure stable and efficient training

The dataset is split into training and testing sets to evaluate generalization performance

🏗️ Model Architecture

A custom object detection architecture is implemented

The model includes:

A feature extraction backbone

A bounding box regression head

An object classification head

All model weights are initialized randomly

No pre-trained weights are used, strictly following assignment requirements

The architecture is designed to balance detection accuracy and computational efficiency

🔁 Training Methodology

The model is trained using supervised learning

Training is performed over multiple epochs

A combined loss function is used to optimize:

Object classification accuracy

Bounding box localization precision

Epoch-wise training logs are monitored to ensure proper convergence.
<img width="723" height="477" alt="Screenshot 2026-01-07 063823" src="https://github.com/user-attachments/assets/d56a8887-a97e-46a9-a93b-9806b938c5e0" />

<img width="995" height="687" alt="Screenshot 2026-01-07 064358" src="https://github.com/user-attachments/assets/ed4bfe3f-a278-4490-a112-57c654bd196d" />


Data normalization and batching are used to stabilize training

📊 Evaluation Metrics

The trained model is evaluated using standard object detection metrics:

mAP (mean Average Precision):
Measures detection accuracy by comparing predicted bounding boxes with ground-truth annotations across all object classes.

FPS (Frames Per Second):
Measures inference speed and helps evaluate real-time performance capability.



These metrics together help analyze the trade-off between accuracy and speed, which is critical for real-world deployment.

🎞️ Real-Time Inference GIF

The following GIF demonstrates the real-time object detection process, showing bounding boxes and predicted class labels:
![prediction](https://github.com/user-attachments/assets/05840faa-a845-4ab0-91ec-d1500d47db12)

📄 Detailed Report

A comprehensive report is included, covering:

Dataset preparation and preprocessing

Model architecture design

Training logs and outputs

Evaluation metrics (mAP & FPS)

Inference results with images

🧾 Conclusion

This assignment demonstrates a complete understanding of object detection by implementing and training a model entirely from scratch.
The project covers dataset preparation, model architecture, training methodology, evaluation metrics, and inference visualization, fulfilling all assignment requirements.












