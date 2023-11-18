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

1. The project employs the MediaPipe library to perform pose detection in images. The pose.process() function is used to analyze the input image and extract pose landmarks.
   ``` python
   results = pose.process(cv2.cvtColor(sample_image, cv2.COLOR_BGR2RGB))

   if results.pose_landmarks:
       for i in range(2):
           print(f'{mp_pose.PoseLandmark(i).name}:\n{results.pose_landmarks.landmark[mp_pose.PoseLandmark(i).value]}')
   ```

3. 

## Results

![Tree Pose Input](https://github.com/Prachi-Lal/Pose-Detection-on-Images/blob/main/tree%20pose%20input.png)
![Tree Pose Landmark](https://github.com/Prachi-Lal/Pose-Detection-on-Images/blob/main/tree%20pose%20landmark.png)
![Tree Pose Output](https://github.com/Prachi-Lal/Pose-Detection-on-Images/blob/main/tree%20pose%20output.png)
![Warrior Pose Detection](https://github.com/Prachi-Lal/Pose-Detection-on-Images/blob/main/warrior%20pose%20detection.png)

## Contributing

Contributions to this project are welcome. If you find any issues or want to enhance the recommendation system, feel free to submit a pull request.

## Acknowledgments

- The dataset used in this project is sourced from [https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).
- The Bag of Words approach is inspired by various research papers and online tutorials.


