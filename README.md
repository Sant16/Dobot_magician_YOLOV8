# Dobot_magician_YOLOV8

This project employs the Dobot Magician Robot to assemble a water filter based on charcoal.

We use the YOLOv8 version from Ultralytics to train a model capable of identifying the following objects:

    funnel
    base
    adhesive tape

The idea is to use a webcam as the robot's eyes, calibrating distances using various techniques. For this purpose, a script is employed that utilizes OpenCV to draw a line 545 pixels long, which should correspond to a length of 30 cm on the surface. This is achieved by adjusting the height of the webcam.
