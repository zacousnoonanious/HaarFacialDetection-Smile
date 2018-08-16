HaarFacialDetection+Smile

Facial detection using Haar cascade classifiers.

Imports: numpy and cv2

Uses pretrained models found from haarcascade_...xml files

2 files created.

The first 'face_recognition_via_file.py' allows specifying the path of an image.
The second 'face_recognition.py' allows webcam access and performs realtime facial and smile detection from source.

Note, video_capture = cv2.VideoCapture(0) where 0 is for internal webcam, and 1 is for external webcam such as USB peripherals.
'z1.jpg' was for my test, but may be replaced with a relative or absolute path to a file of your choice.
