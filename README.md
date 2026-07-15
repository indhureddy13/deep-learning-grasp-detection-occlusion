# Deep Learning-Based Multi-Object Robotic Grasp Detection using CNN and SAM

## Overview
This project implements a deep learning framework for robotic grasp detection in cluttered and occluded environments. A Convolutional Neural Network (CNN) predicts grasp center coordinates, while the Segment Anything Model (SAM) segments individual objects for multi-object grasp localization.

## Features
- Multi-object grasp detection
- CNN-based grasp prediction
- Segment Anything Model (SAM)
- K-Means clustering
- OpenCV image preprocessing
- TensorFlow model training

## Technologies Used
- Python
- TensorFlow
- OpenCV
- NumPy
- Scikit-learn
- Segment Anything (SAM)
- PyTorch

## Dataset
Cornell Grasp Dataset

## Repository Contents
- `DL_Project.ipynb` – Complete implementation
- `Team28_DL_Report.docx` – Project report
- Sample input/output images

## Results
The model successfully detects grasp centers for multiple objects in cluttered scenes and visualizes grasp rectangles after SAM-based segmentation.
