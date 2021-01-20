## Face detection with OpenCV and deep learning

Fast and accurate face detection from **images** and **webcam feed** with OpenCV using a pre-trained deep learning face detector model shipped with the library.

The deep learning model used is the the **Single Shot Detector (SSD)** framework with ResNet as the base network.

### Content

```
OpenCV-FaceDetection
│   README.md   
│
└───ImageDetection
│   │   README.md
|   |   deploy.prototxt.txt
|   |   detect_faces.py
|   |   res10_300x300_ssd_iter_140000.caffemodel
|   |   img1.jpg
|   |   img2.jpg
│   │
│   └───output
│       │   img1.jpg
│       │   img2.jpg
|
└───VideoDetection
        deploy.prototxt.txt
        res10_300x300_ssd_iter_140000.caffemodel
        detect_faces_video.py  
```
