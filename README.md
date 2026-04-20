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
Tympanic_Membrane/
│
├── tympanic_membrane.ipynb


## Model Performance
| Model   | Metric      | Score  |
|--------|------------|--------|
| YOLOv8 | mAP@50     | 97.9%  |
| U-Net  | Dice Score | 88%    |

## Results
The model generates color-coded segmentation overlays:
- Red → Congestion  
- Blue → Perforation  
- Yellow → Retraction  

## How to Run
1. Clone the repository
2. Install dependencies
3. Run the notebook

## Future Improvements
- Real-time detection system  
- Web or mobile deployment  
- Larger dataset for better generalization  

## Author
Srija Roy  

## License
This project is for academic and research purposes. 
