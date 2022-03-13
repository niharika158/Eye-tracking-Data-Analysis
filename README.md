# Mobile Eye-Tracking Data Analysis using ObjectDetection via YOLO v4

 In this work, we explore the opportunities of6using object recognition models to assign mobile eye–tracking data to real objects during an authentic7students’ lab course.  In comparison of three different Convolutional Neural Networks (CNN), Faster Region-based–CNN, YOLO (You only look once) v3, and YOLO v4, we found that YOLO v4 together with an optical flow estimation provides the fastest results with the highest accuracy for object detection in this setting. The automatic assignment of the gaze data to real objects simplifies the time–consuming analysis of mobile eye–tracking data and offers the opportunity for real-time system responses to the user’s gaze. Additionally, we identify and discuss several problems when using object detection for mobile eye-tracking data that need to be considered

![Disparity Output](https://github.com/niharika158/Eye-tracking-Data-Analysis/blob/main/yolov4.png)

This repository provides sample codes for training yolov4 model, mapping gaze coordinates to detected objects coordinates.
In the Yolov4 notebook file contains commands using which yolov4 model can be trained. 
We used this repository https://github.com/AlexeyAB/darknet to train yolov4 model for our custom dataset.
p26_1920.txt is the test results of trained yolov4 model. For each frame it displays classes detected together with the bounding box coordinates and confidence score.

Sensors 2021, 21(22), 7668; https://doi.org/10.3390/s21227668 Human Activity Recognition Using Wearable Sensors for Learning and Teaching) · Nov 18, 2021
