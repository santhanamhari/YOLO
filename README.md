# YOLO

We implement YOLO, a state of the art real-time object detection system. The goal is to regress the bounding boxes and class probabilities with a single network. The ground truths are defined based on grid cells that split up the image. Each ground truth is assigned to a ground truth bounding box with the channels defined as: P(objectness), x, y, w, h, and class probabilities (pedestrian, traffic light, car). Then each image is fed through the model architecture and a loss function is used for optimization. Finally, in inference, we perform postprocessing using non maximum suppression. 

## Model Architecture

<img width="906" alt="Screen Shot 2022-01-19 at 2 22 54 AM" src="https://user-images.githubusercontent.com/40223805/150083533-30bc5120-e836-4f54-8fb2-5c5f6324d6c7.png">

## Training Pipeline

<img width="583" alt="Screen Shot 2022-01-19 at 2 25 10 AM" src="https://user-images.githubusercontent.com/40223805/150083652-a297d6ba-beed-4f6f-8234-939ce28bb43e.png">

## Training Details


<img width="747" alt="Screen Shot 2022-01-19 at 2 26 56 AM" src="https://user-images.githubusercontent.com/40223805/150083939-9c357d12-b54b-4731-a245-15141a04e649.png">

# Results




<img width="175" alt="Screen Shot 2022-01-19 at 2 34 12 AM" src="https://user-images.githubusercontent.com/40223805/150084970-9d795241-c3f4-4781-b04a-09dc7130f32f.png"> <img width="181" alt="Screen Shot 2022-01-19 at 2 34 17 AM" src="https://user-images.githubusercontent.com/40223805/150084973-b23e528b-3d73-485a-a3e3-334548f78fc5.png">
