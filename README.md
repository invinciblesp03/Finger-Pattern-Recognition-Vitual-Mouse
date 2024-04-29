# Finger-Pattern-Recognition-Vitual-Mouse
My first python-based machine Learning Project 

Loras College
Machine Learning
4/19/2024
Finger Pattern Recognition Virtual Mouse Project

Project summitted by Shree Prakash Shah
Project Supervisor: Professor Joshua Morris

Project Overview
The “Finger Pattern Recognition Virtual Mouse” project aims to create a hands-free mouse control system which utilizes the live feed from the webcam and the movement tracking techniques. Users can control the cursor and perform mouse functions without physical contact with the system by detecting the hand movement and gestures.
Project Description 
This project is a fingertip identification and hand gesture recognition-based machine learning project that utilizes computer vision techniques to analyze live webcam feed for hand detection. Once detected the hand, it bounding box is created around the hand to focus on the specific fingers, namely the forefinger and the middle finger for this project. The forefinger serves as the cursor which allows the user to move it around the screen by moving their hand. Additionally, clicking actions are performed when you join your fore finger and your middle finger. 
Important Notes
During the project development, several dependency issues were encountered which were addressed with the following solutions.
•	Autopy not installing: This occurred due to the incompatibility of the Python version. I had to degrade it from the latest to version 3.8.
•	Webcam not opening: There was a bug found in Mediapipe which was later resolved with a change in python version.


Phase I – Data Preparation and Preprocessing
For this project, there was no requirement to collect data beforehand rather, the program would collect the data at the current time and utilize it to run the program.

Phase II – Model Development and Training
This project uses Mediapipe framework, OpenCV library and Autopy library to complete this project. More details of each is given below:
This project required me to install the following modules:
•	OpenCV: A powerful open-source library for computer vision, supporting various programming languages. This enables image and video processing for object detection, facial recognition and more.
•	Mediapipe: A framework which facilitates the development of multimodal machine learning pipelines across different platforms. It supports applications which involve video, audio, and other time series data.
•	Autopy: A cross-platform GUI automation library for Python, enabling control over keyboard and mouse actions, color recognition, and display alerts.
After utilizing all of these, there were some smoothness issues with the cursor so a smoothness factor was later added to the program. Other than that, everything seemed to work fine.

Phase III – Model Evaluation and Deployment
For Phase III of this project the cursor smoothness and its function are used as evaluation metrics to display effectiveness of the project. This project would be on my GitHub repository under the username “Invinciblesp03”. This project can be accessible to all on my GitHub to be able to replicate. This project does not require re-training since the dataset for this project is any hand. It collects the data at the current time so changing the data which is palm would not change the outcome.

Code
The code for this project is dropped to the Elearn dropbox in a zipped file.

