# Machine Learning 🧠✨

Some very basic introductory notes starting from scratch.


## Analyzing the Problem
* predict something?
* create something?
* reccomend something?

## Data Collection
* a lot of data needs to be collected
* the data needs to be cleaned
* you have to select what you want from that data

## Pick a Model
* what algorithm should you use to solve this problem?
* what algorithm is most appropriate?

## Train the Model
* you need to train the model
* you need to then validate / test the model
* test it's accuracy
* does it make sense? did something?
* then REPEAT keep tweaking and improving until it cant be improved

## Main Steps
* picking the correct algorith
* picking the correct data

## Practice Algorithms
* Linear Regression
* K-Nearest Neighbors
* Support Vector Machines

## Some Directions
* Q Learning (for training video games etc)
* Neural Networks (good for everything kindof)

## Learn your Language
* know the basics of your chosen language
* R is specifically for machine learning
* python is the industry standard

--- 

## Neurons
* functions whose goal is to have the right output for an input
* referred to sometimes as neurons (?)
* they each say whether a given image is a hotdog or not (1 or 0)
* the inputs are everything from an individual input 
* like all the pixels from image
* they have randomly initialized internal variables / parameters (?)
* outputs are also referred to as neurons

## Compiling
* loss: measures how well or badly a model did
* optimizer: based on loss generates next guess 
* next guess defined by internal variables in functions

## Epochs
* how many times the compiling process is repeated

## Convolutions
* random guesses are ok but not optimal
* convolutions isolate one aspect of inputs sometimes / often with filters (?)
* there could be hundreds of filters / convolutions
* help the neurons pay attention to things humans care about

## Filter
* defines a convolution
* in images creates new value for all pixel value
* always / sometimes based on pixel's neighbor values (?)
* isolate things like vertical lines, edges, eyes etc.

## Pooling
* used in combination with convolutions / filters
* in images lowers resolution and (can) amplify extremes (?)
* take the darkest pixel in a group of 2x2 pixels
* make it a 1x1 with that extreme value

---

## Workspaces
* in google colab you can use linked notebooks
* pycharm is a more traditional ide

## Feature Columns
* breaking 

## Keras
* another library like tensorflow (?)
* a subordinate library to tensorflow (?)
* ie tf.keras(...)

## Layers
* convolutions and poolings are examples of layers
* there are dozens of other layer types for other datatypes
* there are custom community-made layers as tensorflow addons

## TensorBoard
* visualizer to help track a models progress

## ResNet-50
* popular machine learning model for image classification

## MirroredStrategy
* a method that distributes model training across multiple gpus
