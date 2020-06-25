# Graduation-Project

Summary:
The idea behind this model is to design a neural network model which consists of a convolutional layer, an LSTM layer and a dense layer.
The model should work as an image classifier, on the Fashion MNIST data set as a starter.

I started with the convolutional layer, since CNNs have proven to work well with image classification.
Then, I added a self-implemented LSTM layer to use the statefulness of this layer to try and make my model have a “second look” at samples, which the model wasn’t certain enough
of.
At the end, a classical MLP layer was added to reproduce the probabilities vector and hence the prediction/output.

