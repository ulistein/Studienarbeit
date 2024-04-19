# Workshop Introduction

This Workshop is created to give a introduction to creating a machine learning model with given Data. 

In the end there should be functioning modell to port on the conveyorbelt model from Fischertechnik.

The workshop is designed in a step by step approach consisting of the following steps:
1. Inspection of the data
2. Creating training end evaluation sets
3. Design a machine learning model and train it
4. Evaluate and optimize the model
5. test the model on the application

The workshop starts with a classification model and has the option to create a other architecture if there is enough time left.

Included are three jupyter notebooks one with the tasks and two solution sheets, one for the simpler model and one for the adavnce architecture.

Also included are the datasheets of the conveyorbelt model and the txt4.0 controller as well as the project to control the conveyor belt.

At last there is the dataset, structured in two different ways.

## Requirements
The workshop has a few requirements which need to be met.
1. Installation of the ROBO Pro Coding IDE
1.1 https://www.fischertechnik.de/de-de/schulen/apps-und-software
2. Python with pip and follwoing Modules
    2.1 matpoltlib -> pip install matplotlib
    2.2 numpy -> pip install numpy
    2.3 cv2 -> pip install opencv-python
    2.4 tensorflow -> pip install tensorflow
3. Jupyter Notebook 
4. A good GPU or Google Colab to run the training

## Execution
The execution and Tasks are documented in the Sortingline.ipynb do the Task once for a classification model, and then for a advanced model where to outputs are generated. 

## about the steps
Here are a few sentences about the steps of the workshop and what should be accomplished with those.

### 1. Inspection of the Data
This should give an overview about the ata given with this workshop and should answer how many classes there are and the dimension of the pictures.

### 2. Creating training end evaluation sets
Here are two different techniques shown to establish a training and a validation set. Both ways have pros and cons, explore them.

### 3. Design a machine learning model and train it
Now it is the time to design the first architecture for a machine learning model. In the first approach it will be a classification model depending on the training set you choose. 

The second architecture will add a second output to the mix.

This step also shows the two ways of designing a TensorFlow model, sequential and functional.

### 4. Evaluate and optimize the model
The first model is trained, now it comes to the performance and how to tweak it analyze the performance by the use of the evaluation set.

Now take the steps to optimize the model and train again.

repeat this until you are satisfied with the result.

### 5. test the model on the application
After the model is passing the evaluation it is time to test it at the real application. Export the Model to tflite and transmit it to the controller.

## After the first run
After the first model is loaded and tested on the conveyor belt, you can get to the next model and start again by creating the dataset accordingly.

## Success
After absolving the tasks you have creating your own AI. Congratulations, you did well.
