# Tympanic Membrane Abnormality Detection & Segmentation

## Overview
This project presents an end-to-end deep learning pipeline for detecting and segmenting abnormalities in the tympanic membrane (eardrum) using otoscope images. It focuses on three key conditions:
- Congestion  
- Perforation  
- Retraction  

The system combines object detection and image segmentation to provide accurate and interpretable results for medical analysis.

## Features
- Object detection using YOLOv8  
- High accuracy: 97.9% mAP@50  
- U-Net based segmentation (88% Dice Score)  
- Color-coded overlay visualization for interpretation  
- GPU-accelerated training on Kaggle (Tesla T4)  

## Tech Stack
- Python  
- PyTorch  
- OpenCV  
- YOLOv8  
- Kaggle GPU  

## Project Structure
