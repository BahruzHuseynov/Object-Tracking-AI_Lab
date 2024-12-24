<div align="center">
   <h1>2D Lego Tracking - Object Tracking</h1>
   <h2>AI Laboratory Work (ELTE 2025 - Summer Work + Autumn Semester)</h2>
</div>
<img src = "https://eduscope.me/storage/app/media/pages/affiliated%20universities/LOGOS/ELTE.jpg">

It is a research based project in which object detection, segmentation, and tracking algorithms focusing on LEGO bricks in real-world video recordings are used. Using YOLOv8 and RT-DETR models for the detection, DeepLabv3 for semantic segmentation and DeepSORT for tracking, the research evaluates performance in building an object counter. 

# Technology
- **Python**: Main programming language. ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
- **PyTorch**: Machine Learning framework. <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/PyTorch-Dark.svg" alt="PyTorch" width="30" />
- **Ultralytics**: AI platform that makes the usage of YOLOv8 and RT-DETR models easy. <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTSDfTFONBFO8j91aS1lQPb9jfARtTFP1B82Q&s" alt="Ultralytics" width="50" />
- **OpenCV**: Used for controlling video frames and processing them. <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/OpenCV-Dark.svg" alt="OpenCV" width="30" />
- **RoboFlow**: It is a platform used to annotate images with boundary boxes <img src = "https://d7umqicpi7263.cloudfront.net/img/product/8305253e-2066-4396-9e9a-f0f9b97e75b9.png" alt = "RoboFlow" width = "90"/>

## Google Colab <img src="https://algotrading101.com/learn/wp-content/uploads/2021/05/Google-Colab-Guide-e1620759490851.jpg" alt="Colab" width="50">
- To train or fine-tune detection and segmentation models, usage of GPU is recommended
- During research, Codes have been executed in Google Colab as it is a hosted Jupyter Notebook service that provides free access to computing resources, including GPUs and TPUs.

## Dataset
In this research, the dataset was manually created using a smartphone, consisting of 12 videos — 10 for training and 2 for testing. These videos capture conveyor belts with LEGO bricks from multiple angles with varying complexities for diversity. LEGO bricks were annotated frame-by-frame using RoboFlow (https://roboflow.com/), which was the most time-consuming step. Dataset is publicly available in kaggle: https://www.kaggle.com/datasets/hbahruz/multiple-lego-tracking-dataset

## Using this project

### Acknowledgments
This project leverages the following tools and frameworks:

