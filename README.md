
# Volume-control-using-Hand-Gesture-using-Python-and-OpenCV

Gesture recognition helps computers to understand human body language.In this project for gesture recognition, the human body’s motions are read by computer camera. Thecomputer then makes use of this data as input to handle applications. The objective of this project is to develop an interface which will capture human hand gesture dynamically and will control the volume level.

NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.

Pycaw : Python Audio Control Library

Mediapipe is an open-source machine learning library of Google, which has some solutions for face recognition and gesture recognition, and provides encapsulation of python, js and other languages. MediaPipe Hands is a high-fidelity hand and finger tracking solution. It uses machine learning (ML) to infer 21 key 3D hand information from just one frame. We can use it to extract the coordinates of the key points of the hand.


## Working Principle

The camera in our device is used for this project. It detects our hand with points in it so as it can see the distance between our thumb finger tip and index finger tip. The distance between the points 4 and 8 is directly proportional to the volume of device.

## APPROACH
-Detect hand landmarks.

-Calculate the distance between thumb tip and index finger tip.

-Map the distance of thumb tip and index finger tip with volume range. For my case, distance between thumb tip and index finger tip was within the range of 30 – 350 and the volume range was from -63.5 – 0.0.

-In order to exit press ‘Spacebar'




## Packages Used
1. CV2
2. MediaPipe
3. Ctypes
4. Comtypes
5. Math
6. PyCaw
7. Numpy
## OS used
Windows 10