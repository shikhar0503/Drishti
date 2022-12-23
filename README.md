# Drishti

## ![license](https://img.shields.io/github/license/DAVFoundation/captain-n3m0.svg?style=flat-square)![Project Status](https://img.shields.io/badge/ProjectStatus-Completed-orange)[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
![Python Badge](https://img.shields.io/badge/Python-3.8-success)![Dependency](https://img.shields.io/badge/Dependencies-Tensorflow%20%7C%20Flask%20%7C%20Mediapipe%20%7C%20OpenCV-critical)


![GIF](https://github.com/shikhar0503/Drishti/blob/main/static/assets/Drishti.gif) <br>

Project Drishti is basically a gesture to speech convertor. The general definition of gesture recognition is the ability of a computer to understand gestures and execute commands based on those gestures.

The reason for naming this project _Drishti_ is because I made the use of __"Drishti"__(Vision) of machines to recognize the hand gestures of the subject (in our case a person) and predict the corresponding alphabet. I have also made the use of text to speech convertor to provide a voice enabled output.

### Input Data-
The input for this project is the [MNIST Gesture recognition dataset](https://www.kaggle.com/datamunge/sign-language-mnist).

The American Sign Language letter database of hand gestures represent a multi-class problem with 24 classes of letters (excluding J and Z which require motion) and follows the same CSV format with labels and pixel values in single rows. 

<img src="https://res.cloudinary.com/practicaldev/image/fetch/s--H7kgNN02--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://cdn-images-1.medium.com/max/876/1%2A0xLa5BD6LJfMnGoXJb7wiQ.png" width="500" height ="250">

### Challenges :
- Creating a deep learning model for hand gesture classification. 
- Being able to extract and isolate the hand gestures  as images from OpenCV frames and apply the DL model to the images and return the frames.
- Using flask to create the web app for this project.
- Managing the version conflicts in anaconda.

### Dependencies -
- Python 3.10
- Tensorflow
- Numpy
- Keras
- Flask
- OpenCV
- Mediapipe
- PIL
- Matplotlib


- The output should look like the one given below.

<img src= "https://github.com/shikhar0503/Drishti/blob/main/static/assets/preview.png?raw=true">

### _The repository is open for suggestions. Feel free to open a pull request for improving model accuracy or any other improvements.

### References -
#### [MediaPipe](https://pypi.org/project/mediapipe/)
#### [Flask](https://flask.palletsprojects.com/en/1.1.x/)
