# Real Time Emotion Detection App

This Python code provides a real-time emotion detection application that uses the webcam to detect and analyze facial expressions. The application is built using the Keras library for deep learning and OpenCV for image processing.

## Features

- Detects emotions such as Angry, Happy, Neutral, Sad, and Surprised in real-time using the webcam.
- Displays a circle around the detected face and labels the predicted emotion.
- Provides interactive responses for specific emotions by playing relevant YouTube videos.
- Supports user account creation and login functionality.
- Stores user data in a CSV file for future reference.

## Usage

1. Make sure you have the required libraries installed: Keras, TensorFlow, OpenCV, tkinter, pandas.
2. Run the application by executing `python main.py` in the terminal.
3. The application opens with a login page where users can enter their credentials or create a new account.
4. After logging in, the webcam will start detecting emotions in real-time.
5. Detected emotions are displayed on the screen, and interactive responses are triggered for specific emotions.

## How It Works

1. The application captures video frames from the webcam using OpenCV.
2. It uses a pre-trained deep learning model to detect faces in the frames.
3. Once a face is detected, a region of interest (ROI) is extracted and resized to 48x48 pixels.
4. The ROI is fed into a pre-trained emotion detection model to predict the emotion.
5. Detected emotions trigger specific responses, such as opening web browser tabs to play YouTube videos.

## Note

This code is provided for educational and illustrative purposes. It demonstrates real-time emotion detection using deep learning and user interaction through a graphical interface. Further improvements and optimizations can be made for production-level applications.

For technical support and questions, please contact: ayamullahkhan04@gmail.com
