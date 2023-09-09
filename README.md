
# Digit Recognition

In this project, I took on the ambitious task of developing a neural network from scratch using only linear math and without resorting to any built-in functions or libraries. The main goal is to gain a deep understanding of the basic concepts of neural networks and to create a simple yet fully functional neural network for Digit recognition.


## Dataset

https://www.kaggle.com/competitions/digit-recognizer


## Method

1. Architectural design: 
I started by designing a basic feedforward neural network with an input layer, a hidden layer, and an output layer. Each layer is made up of a number of neurons and I decided to use a sigmoid activation function to introduce nonlinearity. 

2. Maturity difference :
 I implemented a forward-propagation step, which involves summing the weight of the inputs and applying an activation function to each neuron. This process propagates information across the network, from the input layer to the output layer. 

3. Back propagation: 
The implementation of the back-propagation algorithm is an important challenge. I had to calculate the slope for each parameter (weight and bias) of the network and adjust them using gradient descent to minimize the loss function. 

4. Training round: 
I have designed a training loop to iteratively update the model parameters by running forward and backward on the training data. This loop continues until convergence or to a certain number of epochs. 

5. Test and evaluate: 
After training, I evaluated the performance of the model on a separate test dataset.
    
## Challenges:

1. Slope Computation:
Calculating slopes physically was a complex and error-prone task. Investigating and confirming the rightness of angle calculations were noteworthy challenges.

2. Numerical Solidness:
Guaranteeing numerical steadiness when managing with exceptionally little or exceptionally huge numbers in network operations was a steady concern.

3. Hyperparameter Tuning:
Deciding the ideal learning rate, covered up layer measure, and the number of iterations required cautious experimentation and tuning.

