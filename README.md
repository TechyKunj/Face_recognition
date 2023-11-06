##Face Recognition Project

This project demonstrates a simple face recognition system using Python, OpenCV, and Dlib. The code captures frames from the primary camera and detects faces in real-time, drawing rectangles around them and numbering each detected face.

#Prerequisites
Before running this code, make sure you have the following libraries installed:

OpenCV (cv2)
Dlib
NumPY
You can install these libraries using pip:

bash
Copy code
pip install opencv-python dlib numpy
Usage
Clone or download this repository to your local machine.

Open a terminal and navigate to the project directory.

Run the following command to start the face recognition system:

bash
Copy code
python face_recognition.py
You can quit the system by pressing the 'q' key.

##How it Works
The code captures frames from the primary camera using OpenCV (cv2.VideoCapture).

It uses Dlib's face detector to identify faces in the frames.

For each detected face, it draws a green rectangle around it and numbers each face.

##Contributing
Feel free to contribute to this project by creating pull requests or reporting issues.

##License
This project is licensed under the MIT License - see the LICENSE file for details.

##Acknowledgments
The face detection is powered by Dlib's frontal face detector.
