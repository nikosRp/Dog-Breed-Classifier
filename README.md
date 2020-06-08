[//]: # (Image References)

[image1]: ./img/sample_dog_output.png "Sample Output"

## Project Dog Breed Classifier

## Project Overview

In this project, which is part of Udacity's nanodegree program, we are are using Convolutional Neural Networks (CNNs) to create a dog breed classifier. At first we create a classifier using the VGG-16 pretrained network, and we also use Transfer Learning to create a better classifier.  

![Sample Output][image1]


## Getting started

You can review the code and my answers for this project in the dog_app.ipynb file

You can also clone the original project and implement your own solution for this project from [here](https://github.com/udacity/deep-learning-v2-pytorch)

Or simply : 
```
git clone https://github.com/udacity/deep-learning-v2-pytorch.git
cd deep-learning-v2-pytorch/project-dog-classification
```
## Prerequisites
You can see all the prerequisites needed in the requirements.txt file
Or you can install them using:
```
pip install -r requirements.txt
```
I used Anaconda to create a virtual environment on Windows OS
You can check how to use Anaconda and virtual environments [here](https://www.anaconda.com/products/individual)

You will also need to download these datasets:
1.  [Dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
2.  [Human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`. 

You can run and train this network both on CPU and on GPU.
It is suggested to run on GPU in order to speed up the computational time

