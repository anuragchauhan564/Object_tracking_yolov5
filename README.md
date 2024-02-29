# Object-Tracking-PyTorch-YOLOv5-DeepSort
- To develop a robust object detection and tracking system utilizing YOLOv5 for real-time object detection and DeepSort for precise object tracking. The aim is to create an efficient and accurate solution capable of identifying and tracking multiple objects simultaneously in complex environments. By integrating state-of-the-art deep learning techniques, the project seeks to enhance object detection and tracking capabilities, contributing to advancements in computer vision applications.

- This project implements object detection using YOLOv5 and object tracking using DeepSort in PyTorch.


## Usage
##### Clone the repository:
       git clone  https://github.com/ZQPei/deep_sort_pytorch/tree/master

- clone the YOLOv5 repository

## Create a Environment
       conda create -n DeepSortEve python=3.7 
## Activate the environment
       conda activate DeepSortEve 

## Install the requirements
       pip install -r yolov5/requirements.txt 

## CPU Only
       conda install pytorch==1.7.0 torchvision==0.8.0 torchaudio==0.7.0 cpuonly -c pytorch 

       pip install easydict 

       python detect_sort.py --weights yolov5s.pt  --img 640  --source pedestrian.mp4 

![Demo](img.gif)


