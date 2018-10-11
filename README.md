# FrontEnd-EmotionDetection
This is a real-time Emotion detection using [TensorFlow.js](https://js.tensorflow.org/) to load a pretrained model into the browser .
## Abstract 
* This repository use two methods to detect faces:

  1. [Chrome Shape Detection API](https://www.chromestatus.com/feature/4757990523535360)
  2. [face-api.js](https://github.com/justadudewhohacks/face-api.js/)

* Microsoft [FERPlus](https://github.com/Microsoft/FERPlus) as the dataset to train the emotion-detect model. And use [TensorFlow.js converter](https://github.com/tensorflow/tfjs-converter) convert Keras model to .json file for loading and running Javascript inference.

## Requirements
* For **MobileNetImage.html** and **MobileNetWebcam.html**:

  [Chrome Shape Detection API](https://www.chromestatus.com/feature/4757990523535360) :
FaceDetector: Chrome on Android, macOS, Windows 10 platfrom.
Go to chrome browser ```chrome://flags/#enable-experimental-web-platform-features``` and enable the feature 
<img src="https://i.imgur.com/7JhkpJn.png" width="500">

* For **Yolov2Webcam.html** you can run on Chrome, Safari and Firefox.

## Demo
**Both demos are on our [LAB](http://mirlab.org/index.asp) server**

* [MobileNetImage.html](https://mirlab.org:444/demo/FrontEnd-EmotionDetection/src/MobileNetImage.html)

![](https://github.com/kevinisbest/FrontEnd-EmotionDetection/blob/master/images/tfjs_upload.gif)

* [Yolov2Webcam.html](https://mirlab.org:444/demo/FrontEnd-EmotionDetection/src/Yolov2Webcam.html)

![](https://github.com/kevinisbest/FrontEnd-EmotionDetection/blob/master/images/yolo_webcam.gif)

* [MobileNetWebcam.html](https://mirlab.org:444/demo/FrontEnd-EmotionDetection/src/MobileNetWebcam.html)

![](https://github.com/kevinisbest/FrontEnd-EmotionDetection/blob/master/images/tfjs_webcam.gif)
