# ObjectDetection
Simple application of a pre trained object detection model.
The grouping.py python file contains code for forming groups from the output classes(1000 classes in the model). This is optional if you want to use all 1000 classes.
prdiction.py is the latest file for running the model on test image. The code fetches all images from a foler(folder path can be specified in code) and returns a dtaframe with count of each different object from all images.
