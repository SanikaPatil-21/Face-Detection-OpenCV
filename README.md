# Face Detection Project Using Python and OpenCV

## 1. Project Overview
This project implements a real-time face detection system using Python and OpenCV. It uses a pre-trained Haar Cascade classifier to detect human faces through a webcam.

## 2. Objectives
- Detect human faces in real time.
- Capture video using a webcam.
- Draw rectangles around detected faces.
- Display the number of faces detected.

## 3. Technologies Used
- Python
- OpenCV
- Haar Cascade Classifier
- Webcam

## 4. Project Structure
- face_detection.py: Main Python program.
- requirements.txt: Required Python library.

## 5. Installation
Install the required dependency:

pip install -r requirements.txt

## 6. How to Run
Execute the following command:

python face_detection.py

## 7. How It Works
1. The program initializes the webcam.
2. Each video frame is captured.
3. The frame is converted to grayscale.
4. The Haar Cascade classifier detects faces.
5. Green rectangles are drawn around detected faces.
6. The number of detected faces is displayed.

## 8. Expected Output
The application displays a live webcam feed with rectangles around detected faces and a counter showing the number of faces detected.

## 9. Conclusion
The project demonstrates real-time face detection using Python and OpenCV. It provides a practical introduction to computer vision and image processing.
