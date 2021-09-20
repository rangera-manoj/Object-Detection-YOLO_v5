# Object-Detection-YOLO_v5
Object(Plane) detection using Yolo_v5 by Ultralytics

## Overview
For this project, I will be using the YOLOv5 to train an object detection model. YOLO is an acronym for “You Only Look Once”. A popular architecture due to:
1. Speed (Base model — 45 frames per second, Fast model — 155 frames per second, 1000x faster than R-CNN, )
2. The architecture comprises only a single neural network (Can be optimized end to end directly on detection performance)
3. Able to learn the general representation of objects (Predictions are informed by the global context of image)
4. Open-source.

## Available models
There are a total of 4 models to train, Configuration files of all these models are located in the '/content/yolov5/models' folder. You can select any one of them during training. They are  as follows
1. YOLOv5s  - yolov5 small, about 7 million parameter, file - yolov5s.yaml
2. YOLOv5m - yolov5 medium, about 21 million parameters, file - yolo5m.yaml
3. YOLOv5l  - yolov5 large, about 47 million parameters, file - yolo5l.yaml
4. YOLOv5x  -  yolov5 extra-large, about 87 million parameters, file - yolo5x.yaml

## Resource
Article:- https://dockship.io/articles/6013cea05c9276402bd7a484/training-yolov5-object-detection-model-on-custom-data

Colab Notebook:- https://colab.research.google.com/drive/1jD7E8wZfBCYTtXwFPrDwoYnpXG7POKYL?usp=sharing#scrollTo=xsIDf5m-jgw7

## Test images
![download](https://user-images.githubusercontent.com/90151852/133124184-797eeb0d-5243-4836-bf59-6d8dd7ce47a8.png)

## Dataset
Two folders of 500 computer generated satellite images of planes accompanied with an xml of the bounding box coordinates for each.

The dataset can be download here: https://www.kaggle.com/aceofspades914/cgi-planes-in-satellite-imagery-w-bboxes
