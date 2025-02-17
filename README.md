# 🎉 Object Detection with YOLOv8  

Welcome to the **Object Detection** project! This repository contains code and resources for detecting objects in images using the YOLOv8 algorithm.   

[Explore over 100k datasets and pre-trained models here!](https://universe.roboflow.com)  

## 📸 Dataset Overview  

The dataset consists of:  
- **79 annotated images**  
- Annotations are in the **YOLOv8** format.  

### Pre-Processing Steps  
- Auto-orientation of pixel data (with EXIF-orientation stripping)  
- Resize to **640x640** (Stretch)  

### Data Augmentation  
We applied the following augmentations to increase the dataset's robustness:  
- **50% probability** of horizontal flip.  
- Random Gaussian blur between **0 and 2 pixels**.  

## ⚙️ Getting Started  

### Prerequisites  
Make sure you have the following installed:  
- Python 3.x  
- Required libraries (listed in `requirements.txt`)  

### Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/YOUR_USERNAME/REPOSITORY_NAME.git  
   cd REPOSITORY_NAME