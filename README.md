# alphabetSoup

UTDA Module 19 - Alphabet Soup Challenge

## Challenge Writeup

In this challenge I created 4 Neural Network models in order to predict the success of charity investment opportunities. The goal was to create a model with an accuracy of 75%. The highest accuracy I was able to achieve was 71.8%.  The model that achieved the highest accuracy has 69 neurons and 2 hidden layers.

The First Neural network that I attempted had 72 neurons in 1 hidden layer and used "relu" activation on the hidden layer.  Its accuracy was 53.2%. The first change I made was changing the activation function on the hidden layer to "tanh", this resulting in an accuracy of 53.2%.  This change had no impact on the accuracy.  The next change that I made was to remove the "ASK_AMT" from the feature dataset. For this Neural Network I used 69 neurons in 1 hidden layer and used "relu" activation on the hidden layer, the accuracy of this model increased to 71.8%, a significant improvement over the first 2 models. For the final model I added a second hidden layer and placed 46 neurons on the first layer and 23 on the second hidden layer, I kept the "relu" activation function on both layers.  This model resulted in an accuracy of 71.8%.

Given how close this model come to achieving the goal of 75% accuracy I would continue to attempt to optimize this model in order to achieve the desired accuracy.
