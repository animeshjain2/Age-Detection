# Age-Detection

Person's Age detection in real time as well as through video file using Convolutional neural networks and Caffe Framework is used in this pre-trained model.

## Method:

* Firstly, faces are detected in the frame using the caffe model res10_300x300_ssd_iter_140000.caffemodel.
* Secondly, age of every person is predicted also using caffe models age_net.

## Platform:
* Ubuntu 16.04
* Python 3.8.3

## Python Libraries Used:
* opencv-python
* numpy
* imutils 
* argparse

## Implementation:

* Clone this repo and go to the folder path in terminal.
* Run the below to implement Age Detection:
    * In real time:\
           *python detect_age_cam.py*  \  
     * In pre-captured video:
           *python detect_age_file.py*
       

* Result shows the person's face detection and age bracket with percentage accuracy in which it falls.

