# YOLO

We implement YOLO, a state of the art real-time object detection system. The goal is to regress the bounding boxes and class probabilities with a single network. The ground truths are defined based on grid cells that split up the image. Each ground truth is assigned to each bounding box with the channels defined as: P(objectness), x, y, w, h, and class probabilities (pedestrian, traffic light, car). 

## Model Architecture

<img width="906" alt="Screen Shot 2022-01-19 at 2 22 54 AM" src="https://user-images.githubusercontent.com/40223805/150083533-30bc5120-e836-4f54-8fb2-5c5f6324d6c7.png">

## Training Pipeline

<img width="583" alt="Screen Shot 2022-01-19 at 2 25 10 AM" src="https://user-images.githubusercontent.com/40223805/150083652-a297d6ba-beed-4f6f-8234-939ce28bb43e.png">

## Training Details


<img width="747" alt="Screen Shot 2022-01-19 at 2 26 56 AM" src="https://user-images.githubusercontent.com/40223805/150083939-9c357d12-b54b-4731-a245-15141a04e649.png">
