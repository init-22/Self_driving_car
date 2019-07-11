# Self_driving_car
Used Deep Neural Network to train the model in order to learn the optimal action to take at a particular time; given input images from 3 cameras left, right and center. 
Special thanks to Udacity and Self Driving Car Nanodegree team for making their self-driving-car simulator open source for anyone to use.

In order to train the model follow the following steps.
1) Install all dependencies.
2) Download and Install Unity from: https://store.unity.com/download-nuo
3) Download the prebuilt Self Driving Car Simulator from https://github.com/udacity/self-driving-car-sim, Make sure to install it from the readMe file.
4) Unizip the downloaded folder Udacity's link and you can see Unity Icon in front of the second file in the folder.
5) Open it and click on training mode.
6) Press 'r' to store the data. again press 'r' to start recording and again press it to stop recording. It will generate IMG, folder which contains Images taken from the virtual camera in IMG folder and driving_log file. 
7) After that run the model.py file to train the model by proving the driving_log file location.
8) Traning will take hours and hours, my system took approximately 17 hours but I would recommend you to train it on Colab.
9) Now lets test the model by running auto_drive.py file. do not forget to pass h5 file as a command line argument for eg. python auto_drive.py model-007.h5


I highly recommend watching Siraj Raval's video on it: https://www.youtube.com/watch?v=EaY5QiZwSP4


Get in touch with me if you need any help working on this project.


Isaac,
https://www.linkedin.com/in/isaac-patole/
