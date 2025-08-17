# Real-Time Face Detection with OpenCV

This Python project demonstrates real-time face detection using OpenCV's Haar cascade classifier. It captures video from your webcam, detects faces in each frame, and draws rectangles around them.

## Features

- Real-time face detection using webcam input
- Uses OpenCV's built-in Haar cascade classifier
- Highlights detected faces with colored rectangles

## Requirements

- Python 3.x
- OpenCV (cv2)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Cookies101-cookies/Face-Detector.git
   cd face-detector.py

2. Install dependencies:
   ```bash
   pip install opencv-python

## Usage

1. Run the script with:
   ```bash
   python Face-Detection.py

- A window will open showing the webcam feed.
- Detected faces will be marked with rectangles.
- Press q to quit the program.

## How It Works

- Loads OpenCV's pre-trained Haar cascade for face detection.
- Captures video feed from the default webcam.
- Converts each frame to grayscale.
- Detects faces using detectMultiScale().
- Draws bounding boxes on detected faces.

## Notes

- Make sure your webcam is properly connected.
- Haar cascades are sensitive to lighting conditions and face orientation.
- Performance may vary based on system hardware.





