# keypointbasedprocessrecognition
Keypoint based process recognition for humans

The code is given in the ipynb file in the repo. 

The basic workflow of this project is to get the keypoints of an image (Pose Landmark) through mediapipe. 
The difference between every keypoint and the keypoint at 0 index (nose).
An MLP is used to classify the image into human action : sleeping, calling , sitting 

Dataset used is the [Human Action Detection](https://www.kaggle.com/datasets/emirhanai/human-action-detection-artificial-intelligence) dataset
