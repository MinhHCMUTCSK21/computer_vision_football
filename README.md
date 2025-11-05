# Football Analysis Project

## Introduction

⚽ Soccer Analytics Project
This project aims to build a robust system for analyzing soccer matches using advanced computer vision techniques to extract key insights from video footage.

✨ Features
Object Detection & Tracking: Leverages YOLO, a state-of-the-art object detector, to accurately identify players, referees, and the football. Implements object trackers for smooth and consistent analysis across frames. Includes training of a custom object detector to enhance detection accuracy.

Team Assignment: Employs K-means clustering on pixel data to segment players by jersey color, enabling accurate team assignment.

Advanced Movement Analysis:

Utilizes optical flow to precisely measure camera movement between frames, crucial for accurate player tracking.
Implements perspective transformation to convert pixel-based movements into real-world distances, allowing player movement to be measured in meters rather than pixels.
Performance Metrics: Calculates valuable performance metrics such as a player's speed and total distance covered during gameplay.

![Screenshot](output_videos/screenshot.png)

## Modules Used

The following modules are used in this project:

- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player
