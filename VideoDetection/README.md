## Face detection with OpenCV and deep learning

Fast and accurate face detection from video stream with OpenCV using a pre-trained deep learning face detector model shipped with the library.


## Files
1. ```detect_faces_videos.py```: script containing the code for face detection from webcam video stream
2. ```deploy.prototxt.txt```: file which define the model architecture (i.e., the layers themselves)
3. ```res10_300x300_ssd_iter_140000.caffemodel```: file which contains the weights for the actual layers

## Installation/Running the script
1. Install the necessary libraries

```
$ pip3 install numpy
```
```
$ pip3 install imutils
```
```
$ pip3 install time
```
```
$ pip3 install argparse
```
```
$ pip3 install opencv-python
```

2. Run the script using the three required arguments: ```--prototxt```: path to the Caffe prototxt file, ```--model```: path to the pretrained Caffe model.

```
python detect_faces_video.py --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel

```

## Input

Webcam video stream

## Output


