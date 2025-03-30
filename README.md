# 🔍 Real-Time Weapon Detection Using YOLOv11

This project focuses on developing a real-time object detection system capable of identifying handheld weapons, specifically knives and pistols, using the YOLOv11 model. The primary objective is to enhance security in public spaces and commercial establishments by providing an early warning system for potential threats.
This repository is part of a project submission for the Deep Learning Elective at IE School of Sciences and Technology for the Masters in Business Analytics and Big Data.

## 🛠️ Features

⚡ Real-time detection of knives and pistols

🧠 Fine-tuned YOLOv11 model for improved accuracy

📊 Model performance evaluation using precision, recall, and mean Average Precision (mAP)


## 🏗️ Methodology

***Base Model Selection:*** YOLOv11 was chosen due to its accuracy and efficiency in real-time detection.

***Dataset Selection:** An open-source dataset containing labeled images of knives and pistols was used for training.
[![Kaggle](https://img.shields.io/badge/-Kaggle-20BEFF?logo=kaggle&logoColor=white&style=for-the-badge)](https://www.kaggle.com/code/killa92/map-0-9-guns-and-knifes-detection-yolov11)

***Model Fine-Tuning:*** The base YOLOv11 model was fine-tuned to improve knife detection and trained to recognize pistols.

***Evaluation Metrics:*** The model was tested on unseen images and evaluated using precision, recall, and mean Average Precision (mAP).

***Deployment:*** The trained model was deployed using Streamlit and converted into a .tflite format for Android deployment.

## 🧪 Experimentation & Results

***📓 Jupyter Notebook:*** The entire training, fine-tuning, and evaluation process is documented in the included Jupyter Notebook (weapon_detection.ipynb). The notebook provides:

***Data Preprocessing:*** Loading and preparing the dataset in YOLO format.

***Model Training:*** Fine-tuning YOLOv11 with custom hyperparameters.

***Performance Metrics Calculation:*** Precision, recall, and mAP scores.

***Visualization:*** Bounding box predictions on test images.

## 📊 Model Evaluation Results:
| Object Class | Precision | Recall | mAP50  | mAP50-90 |
|--------------|-----------|--------|--------|----------|
| 🔪 Knife     | 0.615     | 0.615  | 0.524  | 0.265    |
| 🔫 Pistol    | 0.325     | 0.324  | 0.409  | 0.201    |

## Contributors
- Santiago Ramirez Planter
- Nilesh Mukherji
- Matteo Becchis
- Alina Edigareva
- Juan Rafael Quintero Hernández
