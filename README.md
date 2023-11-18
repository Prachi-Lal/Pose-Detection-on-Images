# Pose-Detection-on-Images

This repository contains Python code that utilizes the MediaPipe library to perform pose detection in images. Pose detection is a crucial task in computer vision that involves identifying key body landmarks in an image, enabling a range of applications from fitness tracking to gesture recognition.

## Prerequisites

To run this code, ensure that you have the following dependencies installed:

- Python (version 3.9)
- pandas
- scikit-learn
- numpy
- mediapipe
- open-cv

## Approach

The recommendation system follows these steps to suggest similar movies:

1. Pose Detection: The project employs the MediaPipe library to perform pose detection in images. The pose.process() function is used to analyze the input image and extract pose landmarks.
2. Landmark Analysis: If pose landmarks are detected (if results.pose_landmarks:), the script iterates over a specified range to print information about the detected landmarks.
3. Visualization: The script visualizes the detected pose landmarks on the input image using mp_drawing.draw_landmarks. The resulting image is displayed using Matplotlib.
4. 3D Pose Landmark Plotting: Additionally, the code includes the plotting of 3D pose landmarks using mp_drawing.plot_landmarks.
5. Pose Detection and Classification: The script demonstrates how to apply pose detection to specific images and then proceeds to classify the detected poses using the detectPose and classifyPose functions. The details of these functions are not provided in the code snippets.

## Results

![Tree Pose Input](https://github.com/Prachi-Lal/Pose-Detection-on-Images/blob/main/tree%20pose%20input.png)
![Tree Pose Landmark](https://github.com/Prachi-Lal/Pose-Detection-on-Images/blob/main/tree%20pose%20landmark.png)
![Tree Pose Output](https://github.com/Prachi-Lal/Pose-Detection-on-Images/blob/main/tree%20pose%20output.png)
![Warrior Pose Detection](https://github.com/Prachi-Lal/Pose-Detection-on-Images/blob/main/warrior%20pose%20detection.png)

## Contributing

Contributions to this project are welcome. If you find any issues or want to enhance the pose detection system, feel free to submit a pull request.




