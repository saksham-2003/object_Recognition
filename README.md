# Real-Time-Object-Detection-With-OpenCV

### Description

This project aims to do real-time object detection through a laptop camera or webcam using OpenCV and MobileNetSSD. The idea is to loop over each frame of the video stream, detect objects like person, chair, dog, etc. and bound each detection in a box.

### How to run this code?

**Step 1:** Create a directory in your local machine and cd into it

**Step 2:** Clone the repository and cd into the folder:

**Step 3:** Install all the necessary libraries. I used Windows for this project. These are some of the libraries I had to install:

```
pip install opencv-python
pip install matplotlib
pip install imutils
```

**Step 4:** To start your video stream and real-time object detection, run the following command:

```
python main.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel
```

**Step 5:** To terminate press ctrl+c on windows or 'q' key.
