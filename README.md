# digit-recogniser-model
this is a neural network made from scratch without using pytorch or keras to recognise the handwritten digits

first I imported the database where there were 28 by 28 pixel images hence there were in total 784 pixel data.
So I converted this data to a numpy array of dimensions(n,784) where n refers to the no. of training examples and each of the data had a value ranging from 0 to 1 where 1 means black and 0 means white.
Then I created two numpy arrays ,one for training and one for development. And in every run i shuffled the training data and development data. This was to ensure that the model is trained for almost every possible image.
The network comprised of an input layer, 1 hidden layer and an output layer.
The activation functions used are softmax and sigmoid.


In the end after training, the network gave me roughly around 84% accuracy which can be increased using more layers but that's it for now.
