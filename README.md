# Hand Tracking using OpenCV and MediaPipe

A real-time hand tracking application built with **Python, OpenCV, and MediaPipe**. The project uses a webcam to detect and track hand landmarks in real time.

## About The Project

This project demonstrates real-time hand tracking using computer vision.

The application captures video from the webcam using OpenCV and processes each frame with the **MediaPipe Hand Landmarker**. It detects up to two hands and identifies **21 landmarks** for each detected hand.

The detected landmarks and their connections are displayed directly on the webcam feed. The application also calculates and displays the real-time FPS.

This project can serve as a foundation for applications such as:

- Hand gesture recognition
- Finger counting
- Virtual mouse control
- Gesture-based applications
- Virtual drawing
- Human-computer interaction
- Accessibility applications

## Features

- Real-time hand tracking
- Webcam support
- Tracks up to 2 hands
- Detects 21 landmarks per hand
- Draws hand landmark connections
- Displays real-time FPS
- Simple and lightweight implementation

## Built With

- [Python](https://www.python.org/)
- [OpenCV](https://opencv.org/)
- [MediaPipe](https://ai.google.dev/edge/mediapipe/solutions/guide)

## Project Structure

```text
Hand-Tracking-Using-Opencv/
│
├── app.py
├── requirements.txt
├── README.md
├── LICENSE
├── .gitignore
└── hand_landmarker.task
