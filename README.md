OBJECT DETECTION
=====================

This simple project uses the YOLO and OpenCV to detect objects.

![Example Image](detected/test.jpeg)

Download the pre-trained yolo weight file for COCO dataset [https://pjreddie.com/media/files/yolov3.weights](https://pjreddie.com/media/files/yolov3.weights).

Dependencies:
* opencv-python
* numpy
* argparse

To test this out:
1. Copy your image in the `images` directory.
1. Execute the `detection.py` script with these arguments:
    ```python detection.py -i images/{your-image} -c yolov3.cfg -cl classes.txt -w yolov3.weights```
1. The detected image will show up in a floating window.
1. The detected image will be saved in the `detected` directory with the same name.
