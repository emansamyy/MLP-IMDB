# MLP-IMDB
Multilayer Perceptron for binary classification of reviews (positive or negative) for the IMDB dataset

#data preparation
#vectoring reviews which means if one review has less than 10k numbers it will be filled with zeros
#this is done because the biggest review has 10k and all inputs to the neural
#networn must have the same size


#building the model using Sequential API to create a learning model with layers

#Dense is used in layers to make nodes fully connected

#The model is compiled with the loss function as categorical crossentropy 
#which is generally used for multi-class classification models and produces a one-hot array containing the possible match for each category.
#The optimizer is Adam which is a stochastic gradient descent method. The metric used for judging the performance of the model is accuracy.


# the input data is passed, the numeber of epochs = 10 which represents the hyperparameter that defines the number of time that the algorithm will work
# the batch size = 500 which defines the number of samples to work through before updating internal parameters. 
#verbosity = 1 which means its a progress bar
