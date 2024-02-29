# Object-Tracking-PyTorch-YOLOv5-DeepSort

- This project implements object detection using YOLOv5 and object tracking using DeepSort in PyTorch.


## Usage
- 1 Clone the repository:
-  git clone - https://github.com/ZQPei/deep_sort_pytorch/tree/master

- clone the YOLOv5 repository

## Create a Environment
 run -
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


# Watch Demo:

https://www.youtube.com/watch?v=SnoTsGAR9aY
