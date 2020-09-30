# HandWritten_Digit_Classification
## Introduction:
The problem statement is to classify handwritten digits. The goal is to take an image of a handwritten digit and determine what that digit is. The digits range from zero (0) through nine (9).

## Requirements:
Jupyter Notebook

## Dataset
MNIST Handwritten Digits dataset is used for this task. It contains images of digits taken from a variety of scanned documents, normalized in size and centered. Each image is a 28 by 28 pixel square (784 pixels total). The dataset contains 60,000 images for model training and 10,000 images for the evaluation of the model.

## Algorithm: K-Nearest Neighbors Classifier
Here KNN algorithm is used for the recoginition of handwritten digits in MNIST dataset.
The algorithm is as follows:
* Determine the parameter K = number of nearest neighbours.
* Calculate the distance between query instance and all the training samples.
* Sort the distance and determine nearest neighbours based on the kth minimum distance.
* Gather the category of nearest neighbours.
* Use simple majority of the category of the nearest neighbours as the prediction value of the query instance.




## Pros:
* Simple Algorithm - Easy to understand and explain.
* Versatile — useful for classification or regression
* Training phase is extremely quick because it doesn’t learn any data

## Cons:
* Computationally expensive.
* High memory requirement.
* Prediction stage might be slow. (During large no. of training data)

## The Accuracy of the model is 96 %

## How to Run Code:
* The code files are in running condition and are directly executable.
* To install all the necessary packages at once, install Anaconda

