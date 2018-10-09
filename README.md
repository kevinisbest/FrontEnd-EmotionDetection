# FrontEnd-EmotionDetection
Real-time Emotion detection on browser using TensorFlow.js

This repository use two methods to detect faces:

  1. [Chrome Shape Detection API](https://www.chromestatus.com/feature/4757990523535360)
  2. [face-api.js](https://github.com/justadudewhohacks/face-api.js/)

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

* [MobileNetWebcam.html](https://mirlab.org:444/demo/FrontEnd-EmotionDetection/src/MobileNetWebcam.html)

![](https://github.com/kevinisbest/FrontEnd-EmotionDetection/blob/master/images/tfjs_webcam.gif)
