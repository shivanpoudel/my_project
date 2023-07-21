# Car Recognition

 This program uses imageNet to indentify a vast specturm of cars ranging from Audi to Toyota Innova's > 

![add image descrition here](direct image link here) (program isn't finished there are issues)

## The Algorithm

The program takes training data to train the image recognition model. It uses the validation set to validate the model output, and the model gets written into an onnx file. Using that trained model, the program will select random car images not from the training and validation folders to label the input image correctly.

## Running this project

1. When you first get ahold of this project the first thing you must do is to open a terminal. Make sure that the directory is in the jetson-inference. Make sure you do cd jetson-inference to get into the directory. Next step is you have to run this code. "Running test: python3 imagenet.py --model=models/cars/resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=data/cars/labels.txt 12.jpg output.jpg"
2. After the program has run you will find an output.jpg at the bottom and will automatically refresh as the program has run. (This will show the cars and their title)

[View a video explanation here](video link) (program isn't finished there are issues)
