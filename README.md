# Sports Analysis Project

## Introduction
The objective of this project is to use YOLO, a very advanced AI object identification model, to identify and monitor players, referees, and footballs in a video. Additionally, we will provide training to enhance the model's performance. Furthermore, we will assign players to teams by using Kmeans for pixel segmentation and clustering, taking into account the colours of their t-shirts. Using this data, we are able to calculate the proportion of times a team successfully acquires the ball throughout a match. In addition, we will use optical flow to quantify the displacement of the camera between consecutive frames, so allowing us to precisely assess the motion of a player. In addition, we will use perspective transformation to accurately depict the depth and perspective of the scene, enabling us to track a player's movement in metres instead of pixels. Ultimately, we will compute the velocity of a player and the total distance travelled. This project encompasses a range of principles and tackles practical issues, making it appropriate for individuals at all levels of expertise, including novices and seasoned machine learning experts.


![Screenshot](output_videos/output_img.jpg)

## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player

## Trained Models
- [Trained Yolo v5](https://drive.google.com/file/d/1DC2kCygbBWUKheQ_9cFziCsYVSRw6axK/view?usp=sharing)

## Sample video
-  [Sample input video](https://drive.google.com/file/d/1t6agoqggZKx6thamUuPAIdN_1zR9v9S_/view?usp=sharing)

## Requirements
To run this project, you need to have the following requirements installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas
