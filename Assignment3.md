The goal of this assignment is to implement and use gradient descent (and its variants) with
backpropagation for a regression task. Here you need to implement a feedforward neural
network. This network will be trained and tested using the [california_housing dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html).
1. Create a neural network with 3 hidden layers [(input features -> 128 -> 64 -> 32 ->1),
ReLU activation for hidden layers and linear activation for the output layer.] [3 marks]
2. Implement Adam from scratch for the above model. [6 marks]
You need to make the following plot:
• x-axis: number of epochs, y-axis: training loss and validation loss (2 curves) [2 marks]
3. Implement Nesterov Accelerated Gradient (NAG) from scratch for the above model. [6
marks]
You need to make the following plots:
• x-axis: number of epochs, y-axis: training loss and validation loss (2 curves) [2 marks]
4. Use torch.optim and implement Adam, NAG, Adagrad, Adamax, Adadelta, Vanilla
Gradient Descent for the above model. [3 marks]
You need to make the following plots:
• x-axis: number of epochs, y-axis: training loss (6 curves - each curve corresponding to
one of the optimization methods mentioned above) [1 mark]
• x-axis: number of epochs, y-axis: validation loss (6 curves - each curve corresponding
to one of the optimization methods mentioned above) [1 mark]
5. Verify the synchronization of the Adam and NAG curves when using pre-built libraries
(torch.optim.optimizer) and when implementing from scratch. Plot separate curves to
show it. [1 mark] 
