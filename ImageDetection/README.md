## Face detection with OpenCV and deep learning
Fast and accurate face detection with OpenCV using a pre-trained deep learning face detector model shipped with the library.


## Motivation
Learning and improving my skills in programming/object detection.

## Files
1. ```detect_faces.py```: script containing the code for face detection
2. ```img1.jpg```: input image
2. ```img2.jpg```: input image
3. ```deploy.prototxt.txt```: file which define the model architecture (i.e., the layers themselves)
4. ```res10_300x300_ssd_iter_140000.caffemodel```: file which contains the weights for the actual layers
5. ```output```: contains the input images with rectangle and confidence

## Installation/Running the script
1. Install the necessary libraries

```
$ pip3 install numpy
```
```
$ pip3 install argparse
```
```
$ pip3 install opencv-python
```

2. Run the script using the three required arguments: ```--image```: path to input image, ```--prototxt```: path to the Caffe prototxt file, ```--model```: path to the pretrained Caffe model.

```
python detect_faces.py --image img2.jpg --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel

```

## Results

### Input

<img src="/Users/dumitrescucristian/Desktop/ObjectDetection/OpenCV/ImageDetection/img1.jpg" width="400" height="300">

<img src="/Users/dumitrescucristian/Desktop/ObjectDetection/OpenCV/ImageDetection/img2.jpg" width="400" height="300">

### Output


<img src="/Users/dumitrescucristian/Desktop/ObjectDetection/OpenCV/ImageDetection/outputs/img1.png" width="400" height="300">

<img src="/Users/dumitrescucristian/Desktop/ObjectDetection/OpenCV/ImageDetection/outputs/img2.png" width="400" height="300">
