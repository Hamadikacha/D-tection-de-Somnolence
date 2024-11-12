# Drowsiness Detection with OpenCV

This repo contains code for detecting and tracking a user's eyes, and alerting when the user is feeling drowsy using video processing techniques.

## Code Requirements

The example code is in Python (version 3.7 or higher will work). The code is tested under Ubuntu 20.04.

## Dependencies

The following Python libraries are required to run the code:

- cv2
- immutils
- dlib
- scipy

Additionally, the file "shape_predictor_68_face_landmarks.dat" must be placed in the same directory as the Python scripts.

## Description

This is a computer vision system that can automatically detect driver drowsiness by tracking the closing of the eyes and yawning in a real-time video stream, and then alerting if the driver appears to be drowsy.

## Execution

To run the code, execute the following command:

```
python3 Drowsiness_Detection.py
```

or

```
python3 test-eyes.py
```


Copy and paste the above commands in your terminal to execute the code.

## Demo

Check out the following animation to see the drowsiness detection in action:

![Drowsiness Detection Animation](./Animation%20(gif).gif)

