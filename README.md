## CALIBRATION SYSTEM FOR FACE DETECTION
### OVERVIEW
The repository contains code for the calibration of camera used for face detection, where face-detection is done by detecting the 68 facial landmarks and comparing calibration percentage with a threshold value.
### DEPENDENCIES
1. Dlib
2. Numpy
3. Opencv
### USAGE
>python calibration.py --shape-predictor shape_predictor_68_face_landmarks.dat
### LIMITATION
The code shows multiple calibration percentages in case of detection of multiple faces i.e. the priority for faces could not be set. 
