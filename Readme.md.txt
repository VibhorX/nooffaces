# Real-time Face Detection using Dlib

This Python script demonstrates real-time face detection using the Dlib library. It captures video from the default camera, detects faces in the video frames, and draws rectangles around the detected faces.

## Requirements

- Python 3.x
- OpenCV
- Numpy
- Dlib

## Usage

1. Make sure you have all the required libraries installed (`pip install opencv-python numpy dlib`).
2. Run the Python script (`python face_detection.py`).
3. Position yourself in front of the camera.
4. The script will detect and draw rectangles around your face(s) in real-time.

## Description

- The script uses Dlib's `get_frontal_face_detector` function to create a face detector object.
- It captures video frames from the default camera (you can change the camera index if needed).
- Each frame is converted to grayscale for face detection.
- The Dlib face detector is used to detect faces in the grayscale frames.
- Rectangles are drawn around the detected faces using OpenCV's `rectangle` function.
- The script displays the number of faces detected and assigns a unique number to each detected face.


