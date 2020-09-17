# Facial Expression Recognition
It is made using keras, Tensorflow, Haarcascade classifier, Numpy and opencv-python

## REQUIREMENTS

1. Numpy
2. Opencv-python
3. Tensorflow
4. Keras [Sequential, Dense, Dropout, Activation, Flatten, Conv2D, BatchNormalization, MaxPooling2D]
5. Kaggle Dataset : https://www.mediafire.com/folder/trbjv7bysiycl/challenges-in-representation-learning-facial-expression-recognition-challenge
6. HaarCascade file is available here.

## USAGE

We preprocess the data in the dataset file into train and test data.
x-values are picture pixels.
y-values are emotions as output.
We create  a sequential model in keras using CNN and create 3 layers.
You can use as many layers as you want before fully connecting the model.
We use opencv to read real-time images from our device.
I used 30 epoches[3 hours] which gave me an accuracy of 64%. You van use more epoches to train the data .
