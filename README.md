# Adversarial Robust Traffic Sign Detection for Autonomous Vehicles

##  Overview
This project focuses on improving the robustness of traffic sign detection models under adversarial and adverse weather conditions such as fog, rain, blur, and low visibility. The system is designed for autonomous vehicle perception using YOLO-based object detection.

##  Problem Statement
Traffic sign recognition systems often fail under adversarial environmental conditions, leading to unsafe decisions in autonomous vehicles. This project addresses this challenge by applying targeted adversarial data augmentations to enhance model robustness.

##  Methodology
- Dataset preparation and annotation
- Adversarial weather-based augmentations
- Training YOLO model on clean + augmented data
- Evaluation using precision, recall, mAP, and confidence scores
- Robust inference under unseen adversarial conditions

##  Adversarial Augmentations Used
- Fog simulation
- Rain effect
- Motion blur
- Gaussian noise
- Brightness & contrast distortion

##  Model Training
- Base Model: YOLO
- Training Strategy: Clean + Augmented dataset
- Loss optimization for robust detection

##  Evaluation Metrics
- Precision
- Recall
- mAP@50
- mAP@50–95
- Confusion Matrix (Normalized & Unnormalized)

##  Results
The adversarially trained model shows improved detection accuracy and confidence under adverse conditions compared to the baseline model.

##  Tech Stack
- Python
- YOLO
- OpenCV
- Albumentations
- PyTorch
- Kaggle

##  Project Structure
Refer to the repository structure for organized code, notebooks, and results.

##  Future Work
- Real-time deployment
- Adversarial attack simulations
- Integration with autonomous driving pipelines

##  Author
Meghana S  
4th Year AIML Student
