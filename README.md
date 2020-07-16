# digit_recognization
This project is for recognising digits by drawing them on a screen. Two files named : backend_numbers.py and application_numbers.py are part of this project.
# 1. backend_numbers.py
   This file mainly trains data for further recognisation part.
   In this data-set is taken from inbuilt data-set of Keras named "mnist" data-set. Than reshape images and to train this convolutional neural network(CNN), with 2 Convolution layers and a flatten layer. Then passed through softmax function.
   To compile it "adam" optimiser is used, with learning rate 0.01. And finally our data-set is trained.
# 2. application_numbers.py
   In this file, application part of digit recognisation is given.
   Here, tkinter library of python for creating screen to draw digit we want to recognise than just click on recognise button and result will come with what it has recognise and with what percentage of accuracy.
