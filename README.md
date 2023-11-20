# Ann_titanic_classification

Artificial Neural Network for Titanic Classification

This artificial neural network (ANN) model, implemented using Keras, is designed to classify passengers as survivors or non-survivors based on their characteristics, such as age, sex, cabin class, and fare. The model consists of three fully connected layers:

The first layer has 10 neurons and uses the rectified linear unit (ReLU) activation function.

The second layer has 15 neurons and also uses the ReLU activation function.

The output layer has a single neuron and uses the sigmoid activation function, which produces a probability between 0 and 1, indicating the likelihood of survival for a given passenger.

The model was trained on a dataset containing information about passengers aboard the Titanic, and it achieved a validation accuracy of 69.49%. This suggests that the model can reasonably predict the survival outcome for passengers based on their characteristics.
