# Car Recognition

 This program uses imageNet to indentify a vast specturm of cars ranging from Audi to Toyota Innova's > 

![add image descrition here](direct image link here) (program isn't finished there are issues)

## The Algorithm

The program takes training data to train the image recognition model. It uses the validation set to validate the model output, and the model gets written into an onnx file. Using that trained model, the program will select random car images not from the training and validation folders to label the input image correctly.

Add an explanation of the algorithm and how it works. Make sure to include details about how the code works, what it depends on, and any other relevant info. Add images or other descriptions for your project here. 

## Running this project

1. When you first get ahold of this project the first thing you must do is to open a terminal. Make sure that the directory is in the jetson-inference. Make sure you do cd jetson-inference to get into the directory. Next step is you have to run this code. "Running test: python python/car_recognition/car_recognition.py python/car_recognition/12.jpg" (The program will override the 12.jpg)
2. Nothing is necessary to instal just make sure that the data set has the folders with the names from the labels.txt

[View a video explanation here](video link) (program isn't finished there are issues)
