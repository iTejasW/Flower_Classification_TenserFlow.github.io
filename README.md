# Flower Classification Using Tenserflow

We will be creating a ML model to classify the images of flowers

Make sure to install these requirments into your IDE
from __future__ import absolute_import, division, print_function, unicode_literals
import tensorflow as tf
import pandas as pd
Link for training and testing data:
Training:- "https://storage.googleapis.com/download.tensorflow.org/data/iris_training.csv"
Testing:- "https://storage.googleapis.com/download.tensorflow.org/data/iris_test.csv"


we have 120 entires with 4 features.
This specific dataset seperates flowers into 3 different classes of species.
Setosa
Versicolor
Virginica

The information about each flower is the following.
sepal length
sepal width
petal length
petal width


Here we Used #DNNClassifier, the DNN seems to be the best choice. This is because we may not be able to find a linear coorespondence in our data.
