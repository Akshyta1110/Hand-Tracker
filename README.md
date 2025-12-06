## HAND TRACKER PROGRAM

# DESCRIPTION:
The Hand Tracker Program is a computer vision tool designed to detect and follow the movement of a user’s hand in real time using a webcam or video input. It identifies the position of the hand, tracks finger movements, and recognizes basic gestures with high accuracy. 
Using techniques like skin detection, contour analysis, or landmark-based tracking (such as MediaPipe), the program processes each frame to map hand coordinates smoothly and quickly.

This makes it useful for applications like gesture-controlled interfaces, virtual drawing, touchless navigation, gaming, or accessibility tools. 
The program is built to run efficiently, offering low-latency tracking and a user-friendly experience without needing any external hardware.

# FEATURES:
1. Tracks hand movement in real time

2. Detects finger positions

3. Supports basic gesture recognition

4. Uses MediaPipe/OpenCV

5. Works on webcam input

# INSTALLATION:
For setup install the following programs (please make sure to use pyhton 3.12 version) :
1. pip intall numpy
2. pip install opencv-python
3. pip install mediapipe msvc-runtime

After installing kindly import the following libraries:
1. import cv2
2. import mediapipe.python.solutions.hands as mp_hands
3. import mediapipe.python.solutions.drawing_utils as mp_drawing
4. import mediapipe.python.solutions.drawing_styles as mp_drawing_styles

# WORKING:
1. Captures video frame

2. Detects hand landmarks

3. Draws tracking points

4. Outputs coordinates/gestures

# USE CASES:
1. Gesture control

2. Virtual drawing

3. Touchless UI

4. Gaming interactions

# AUTHOR:
AKSHYTA DHIR 
Git: @Akshyta1110
