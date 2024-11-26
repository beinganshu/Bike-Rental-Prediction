## Project Details:

- Built a neural network from scratch using Numpy
- Implement sigmoid activation function.
- Implement Forward pass in a Neural Network.
- Calculate the Mean Squared Error and Gradients of Error to propagate backwards.
- Implement Backward pass to update the weights of the Network (Gradient Descent).
- Try different - number of hidden layers, learning rates and training iterations.
- After 6000 iterations, _Training loss: 0.058_ and _Validation loss 0.140_ was achieved with a _learning rate: 0.5_ and _Hidden Nodes: 20_.

## Performance:

Following are the Training and Validation losses and the predictions made by the Neural Network:

![Train-Val-Loss](plots/Train-Val-Loss.png)
![Actual-vs-Prediction](plots/Actual-vs-Prediction.png)

## Inferences:

- The neural network doesn't perform well over the period of Dec 22 - 31 as it can be seen from the above plot.
- The reason for this is because the network had never seen the data of Decemeber Holiday Season when people do not generally go to their offices and hence would not be renting bikes.
- This gives us an important insight that the network needs more data to learn these patterns.
- Also, an additional feature in the dataset marking holiday on a particular day could be helpful as well.

## Analysis:

Different learning rates, Number of Iterations and Number of Hidden Nodes were tried to see the effects of these hyper parameters. Following are the analysis produced:

![Changing-Learning-Rate](plots/Changing-Learning-Rate.png)
![Changing-Number-of-Hidden-Nodes](plots/Changing-Number-of-Hidden-Nodes.png)
![Changing-Iterations](plots/Changing-Iterations.png)
![Validation-Loss-Change-on-different-Hyper-Parameters](plots/Validation-Loss-Change-on-different-Hyper-Parameters.png)
