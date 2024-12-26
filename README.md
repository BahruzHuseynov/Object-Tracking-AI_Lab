<div align="center">
   <h1>2D Lego Tracking - Object Counter - Multiple Object Tracking</h1>
   <h2>AI Laboratory Work (ELTE 2025 - Summer Work + Autumn Semester)</h2>
   <img src = "images/ELTE_Logo.png" alt="ELTE Logo">
</div>

It is a research based project in which object detection, segmentation, and tracking algorithms focusing on LEGO bricks in real-world video recordings are used. Using YOLOv8 and RT-DETR models for the detection, DeepLabv3 for semantic segmentation and DeepSORT for tracking, the research evaluates performance in building an object counter. <b> For the detailed information, you can read the report. </b>

## Technology
- **Python**: Main programming language. ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
- **PyTorch**: Machine Learning framework. <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/PyTorch-Dark.svg" alt="PyTorch" width="30" />
- **Ultralytics**: AI platform that makes the usage of YOLOv8 and RT-DETR models easy. <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTSDfTFONBFO8j91aS1lQPb9jfARtTFP1B82Q&s" alt="Ultralytics" width="50" />
- **OpenCV**: Used for controlling video frames and processing them. <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/OpenCV-Dark.svg" alt="OpenCV" width="30" />
- **RoboFlow**: It is a platform used to annotate images with boundary boxes. <img src = "https://d7umqicpi7263.cloudfront.net/img/product/8305253e-2066-4396-9e9a-f0f9b97e75b9.png" alt = "RoboFlow" width = "90"/>
- **Kaggle**: This platform has been used to store data. <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTZtXL5iMUpyo9rv-wJGjZiR62QPubHeI6-wA&s" alt="Kaggle Logo" width="70">

## Google Colab <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSArk3D34rWqNoPw4_n-ovyK0lz3yvknTVZd9yeCdZrsdDEViqoPMmjhFWD-iy4NO1UiyI&usqp=CAU" alt="Colab" width="40">
- To train or fine-tune detection and segmentation models, usage of GPU is recommended.
- During research, codes have been executed in Google Colab as it is a hosted Jupyter Notebook service that provides free access to computing resources, including GPUs and TPUs.

## Dataset
- In this research, the dataset was manually created using a smartphone, consisting of 12 videos — 10 for training and 2 for testing. These videos capture conveyor belts with LEGO bricks from multiple angles with varying complexities for diversity. LEGO bricks were annotated frame-by-frame using RoboFlow (https://roboflow.com/), which was the most time-consuming step.
- Dataset is publicly available in Kaggle: https://www.kaggle.com/datasets/hbahruz/multiple-lego-tracking-dataset

## Pipeline
<div align="center">
   <img src="images/Pipeline_Main.png" alt="Pipeline" width="700">
</div>

## Pre-trained parameters
- The folder contains .pt files of YOLOv8 and RT-DETR detection models which are the saved parameters of best YOLOv8 and best RT-DETR models represented in Lego_Results.xlsx (located under Results folder)

## Models
- Jupyter Notebook named "Fine-Tuning Detection Models" is used to fine-tune the YOLOv8 and RT-DETR and save the parameters
- data.yaml file is used in the training procedure of the detection models, which contains data path, augmentation types and other needy information
- Jupyter Notebook named "Fine-Tuned RTDETR + DeepSORT" is a combination of the Detection-Tracking pipeline. YOLOv8 can also be used instead of RT-DETR with some minor changes.

## Results
- The folder contains Lego_Results.xlsx which has all saved values during the execution of the codes
- There are also some figures underlining important points obtained from the experiments

## <a href="https://drive.google.com/drive/u/1/folders/1BtncxKLn97y3-L2wcXft52zz3Ut1DKeu" target="_blank"> Videos </a>
