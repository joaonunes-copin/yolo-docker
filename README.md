Sagemaker compliant container hosting a custom Yolov3 model compiled with darknet


***This Yolov3 library was compiled to use CUDA, CuDNN on a Tesla Volta GPU - any other 
software/hardware configuration will most likely not work***

You can train a new Yolo model for your target platform and replace the libyolo_volta.so with you Yolo lib


In addition to this repo you MUST:

download aces_4000.weights from http://s3.amazonaws.com/cardbot-data/aces_4000.weights to your 
application directory (236Mb)

download req_libs.zip from http://s3.amazonaws.com/cardbot-data/req_libs.zip AND run libCopy.py
***These libraries are for the CUDA, CuDNN, OpenCV and other dependencies and may change if you re-train a new model


