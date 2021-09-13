# Object-Detection-YOLO_v5
## Object(Plane) detection using Yolo_v5 by Ultralytics

### Overview
For this project, I will be using the YOLOv5 to train an object detection model. YOLO is an acronym for “You Only Look Once”. A popular architecture due to:
1. Speed (Base model — 45 frames per second, Fast model — 155 frames per second, 1000x faster than R-CNN, )
2. The architecture comprises only a single neural network (Can be optimized end to end directly on detection performance)
3. Able to learn the general representation of objects (Predictions are informed by the global context of image)
4. Open-source.

### Test images
![download](https://user-images.githubusercontent.com/90151852/133124184-797eeb0d-5243-4836-bf59-6d8dd7ce47a8.png)

### Dataset
Two folders of 500 computer generated satellite images of planes accompanied with an xml of the bounding box coordinates for each.

The dataset can be download here: https://www.kaggle.com/aceofspades914/cgi-planes-in-satellite-imagery-w-bboxes
