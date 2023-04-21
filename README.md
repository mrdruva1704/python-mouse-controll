# python-mouse-controll

Eye-Controlled Mouse using Mediapipe
This code uses Mediapipe library to track the facial landmarks and control the mouse pointer using eye movements. The code requires a camera to capture the video stream and detects the facial landmarks using Mediapipe's face_mesh model. It then extracts the landmarks for the left eye and checks for the vertical distance between the top and bottom landmarks. If the distance is smaller than a certain threshold value, it simulates a mouse click.

Requirements
Python 3.6 or higher
OpenCV
Mediapipe
PyAutoGUI
Installation
Install Python 3.6 or higher.
Install OpenCV, Mediapipe and PyAutoGUI libraries using pip:
Copy code
pip install opencv-python mediapipe pyautogui
Usage
Connect a camera to your system.
Run the code using:
Copy code
python eye_controlled_mouse.py
Look at the top and bottom landmarks of your left eye to simulate mouse clicks.





Regenerate response
