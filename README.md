# Adversarial Robust Traffic Sign Detection for Autonomous Vehicles

## Project Overview
This project implements an adversarially robust traffic sign detection system designed for autonomous vehicles. The model is trained to perform reliably under adverse environmental conditions such as fog, rain, blur, and low visibility.

##  Objective
To improve traffic sign detection accuracy and confidence in adversarial and challenging weather conditions using data augmentation and robust training.

##  Approach
- YOLO-based object detection model
- Adversarial weather augmentations applied during training
- Training on clean + augmented datasets
- Evaluation using standard detection metrics
- Frontend interface for real-time inference

##  Adversarial Conditions Used
- Fog
- Rain
- Motion blur
- Gaussian noise
- Brightness and contrast variations

##  Evaluation Metrics
- Precision
- Recall
- mAP@50
- mAP@50–95
- Confidence scores

##  Frontend
A simple frontend is provided to upload traffic sign images and visualize detection results with bounding boxes and confidence scores.

##  Technologies Used
- Python
- YOLO
- PyTorch
- OpenCV
- Albumentations
- Kaggle

##  Repository Contents
- `train_and_evaluate.ipynb` – Model training, augmentation, and evaluation
- `frontend_app.py` – Frontend for inference and visualization

##  Author
Meghana S  
4th Year AIML Student
