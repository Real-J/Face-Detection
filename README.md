# Face Detection Using Dlib and OpenCV

## Overview
This project demonstrates real-time face detection using the dlib library and OpenCV. It uses a pre-trained frontal face detector from dlib to detect faces in frames captured from a webcam or video input.

## Features
- **Real-Time Face Detection**: Detects faces in live video feed using dlib's pre-trained frontal face detector.
- **Bounding Boxes**: Displays bounding boxes around detected faces.
- **Cross-Platform**: Works on Windows, macOS, and Linux with Python and OpenCV installed.

## Requirements
To run this project, ensure you have the following installed:

- Python 3.6+
- dlib
- OpenCV
- NumPy

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/face-detection.git
   cd face-detection
   ```

2. Install the required libraries:
   ```bash

  
   pip install dlib opencv-python numpy
   ```

## Usage
1. Run the script:
   ```bash
   python face_detection.py
   ```

2. Press `q` to quit the application.

## Code Explanation
- **Face Detector Initialization**: The dlib's `get_frontal_face_detector()` is used to load the pre-trained face detection model.
- **Video Capture**: OpenCV's `VideoCapture` is used to access the default webcam.
- **Face Detection**: Each frame is converted to grayscale for better performance, and the `face_detector` detects faces in the frame.
- **Visualization**: Detected faces are highlighted using rectangles drawn on the original frame.
- **Exit**: The script stops when the user presses `q`.



## Contributing
Contributions are welcome! If you'd like to add new features, fix bugs, or improve the documentation, feel free to fork the repository and create a pull request.


## Acknowledgments
- [dlib Library](http://dlib.net/)
- [OpenCV Documentation](https://docs.opencv.org/)


