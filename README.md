# Drowsiness-Detection-System
Drowsiness Detection using Eye Aspect Ratio (EAR)

This Python project utilizes computer vision techniques to detect drowsiness in real-time based on the eye aspect ratio (EAR). The EAR is calculated from facial landmarks obtained through face detection. When the EAR falls below a predefined threshold for consecutive frames, an alert is triggered to indicate possible drowsiness.

## How to use:

Install required libraries: scipy, imutils, dlib, OpenCV, and pygame.
Place alarm.wav and shape_predictor_68_face_landmarks.dat in the working directory.
Run the script to start capturing frames from the default camera.
The video feed displays facial landmarks and eye contours.
If eyes are closed for a certain duration (frame_check), an alert message is shown, and an alarm sound is played.

## Customization:

Adjust thresh to set a different EAR threshold for drowsiness detection.
Modify frame_check to change the consecutive frames required for the alert.
Important Notes:

Ensure required files and libraries are available.
This project is for educational purposes and not for safety-critical applications.

## Acknowledgments:

Uses dlib for face detection and OpenCV for image processing.
Alarm sound by pygame.
Pre-trained facial landmark predictor by dlib.
