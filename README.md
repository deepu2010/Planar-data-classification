# Planar-data-classification
In this notebook, I have built a neural network with multiple hidden layers without any deep learning libraries to classify red and blue points in the form a flower.

#### Planar Dataset Visualization:

![Alt Text](https://raw.githubusercontent.com/deepu2010/Planar-data-classification/master/petal%20dataset.JPG)


This project is part of my deep learning specialization course from deeplearning.ai. 

**The key objectives in this notebook is to:**

  * Implement a 2-class classification neural network with a single hidden layer
  * Use units with a non-linear activation function, such as tanh
  * Compute the cross entropy loss
  * Implement forward and backward propagation


#### Neural Network Built:

During my coursework, I have learnt a general methodology to build a Neural Network. The general methodology is as follows:

1. Define the neural network structure ( # of input units,  # of hidden units, etc). 
2. Initialize the model's parameters
3. Loop:
    - Implement forward propagation
    - Compute loss
    - Implement backward propagation to get the gradients
    - Update parameters (gradient descent)

![Alt Text](https://raw.githubusercontent.com/deepu2010/Planar-data-classification/master/planar%20data.JPG)

#### Output Achieved

![Alt Text](https://raw.githubusercontent.com/deepu2010/Planar-data-classification/master/Hidden%20layer%205.JPG)

#### Key activities included in this project

1. Before building my own neural network, I have built a logistic regression machine learning model but I was able to achieve only **47% accuracy**

2. Then, I built a neural network model with a single hidden layer with 4 units, the accuracy is much improved. **Achieved accuracy = 90%**

3. Using trail and error method, I tried adding hidden layers from 1 to 20, based on those observations, I found my model with 5 hidden layers works the best. **Achieved accuracy = 91.5%**

#### Deep Learning Model details:

1. My model can be represented as,

[LINEAR -> TANH] × (L-1) -> LINEAR -> SIGMOID

2. Cost function: **Cross entropy loss functon**
3. Number of hidden units: 5

