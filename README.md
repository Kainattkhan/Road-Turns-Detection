# Road Turns Detection and Classification Project

Welcome to the **Road Turns Detection and Classification** project! 🚗 This repository contains the code and assets for a two-fold task: classifying road turns and detecting them in real-world images. The project is built using **YOLOv8** and achieves high accuracy in both tasks.

## 🗂️ Project Overview

### Task 1: **Classification**
- **Objective**: Predict the type of road turn from the image.
- **Classes**: 
  - Left Turn
  - Right Turn
  - Straight Road
  - Unexpected Turn
- **Performance**:
  - Validation Accuracy: **91%**
  - Test Accuracy: **91%**

### Task 2: **Detection**
- **Objective**: Detect and localize road turns in images using bounding boxes.
- **Tools**: 
  - **Roboflow** for image labeling and dataset preparation.
  - **YOLOv8** for detection.
- **Results**:
  - Bounding boxes with precision and recall metrics.

## 📸 Dataset
The dataset comprises images of roads from **Gilgit-Baltistan**, which feature diverse landscapes and challenging road conditions. It was curated and labeled manually using **Roboflow**.

### Dataset Structure
- road_turns/
  - train/
  - val/
  - test/

## 🚀 Features
- **Robust Classification**: Accurately classifies road types.
- **Precise Detection**: Detects and localizes road turns with YOLOv8.
- **Custom Dataset**: Unique dataset from the scenic roads of Gilgit-Baltistan.

## 🛠️ Setup and Installation
1. Clone this repository:
   git clone https://github.com/Kainattkhan/Road-Turns-Detection.git
  
## 📊 Results
- **Classification Accuracy**: 91% on both validation and test sets.
- **Detection Metrics**: High precision and recall for bounding box detection.

## 🎯 Goals and Future Work
- Further optimize detection performance.
- Expand the dataset with more road conditions.
- Deploy the model as a web application.

## 🤝 Acknowledgments
Special thanks to **Roboflow** for the labeling tool and the incredible scenery of **Gilgit-Baltistan** for making this dataset unique.


Feel free to explore and contribute! 🌟
