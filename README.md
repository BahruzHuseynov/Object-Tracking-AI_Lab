<div align="center">
   <h1>2D Lego Tracking - Object Tracking</h1>
   <h2>AI Laboratory Work (ELTE 2025 - Summer Work + Autumn Semester)</h2>
</div>
<img src = "https://eduscope.me/storage/app/media/pages/affiliated%20universities/LOGOS/ELTE.jpg">

It is a research based project in which object detection, segmentation, and tracking algorithms focusing on LEGO bricks in real-world video recordings are used. Using YOLOv8 and RT-DETR models for the detection, DeepLabv3 for semantic segmentation and DeepSORT for tracking, the research evaluates performance in building an object counter. 

# Technology
- **Python**: Main programming language. ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
- **PyTorch**: If deep learning-based gaze tracking is implemented. <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/PyTorch-Dark.svg" alt="PyTorch" width="30" />
- **Ultralytics**: <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTSDfTFONBFO8j91aS1lQPb9jfARtTFP1B82Q&s">
- **OpenCV**: Used for capturing video feed and processing the gaze data. <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/OpenCV-Dark.svg" alt="OpenCV" width="30" />
- **MediaPipe**: Open-source framework for building pipelines to apply computer vision inference over video. <img src = "https://viz.mediapipe.dev/logo.png" alt = "MediaPipe" width = "30"/>
- **PyAutoGui**: Graphic User Interface for creating the Breakout game. <img src = "https://miro.medium.com/v2/resize:fit:1200/0*N2n8UFCISGIEr1lH.jpeg" alt = "PyAutoGUI" width = "50" />
- **NumPy**: For efficient array manipulation and calculations. <img src = "https://user-images.githubusercontent.com/50221806/86498208-af4bfe00-bd39-11ea-88fa-c747ae0ddd85.png" alt = "NumPy" width = "30"/>

## Prerequisites
- Creation of the virtual environment is recommended


## Using this project

## Dataset
In this research, the dataset was manually created using a smartphone, consisting of 12 videos — 10 for training and 2 for testing. These videos capture conveyor belts with LEGO bricks from multiple angles with varying complexities for diversity. LEGO bricks were annotated frame-by-frame using RoboFlow (https://roboflow.com/), which was the most time-consuming step. Dataset is publicly available in kaggle: https://www.kaggle.com/datasets/hbahruz/multiple-lego-tracking-dataset

### Acknowledgments
This project leverages the following tools and frameworks:

