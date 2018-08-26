You will use the processed dataset to build a neural net. The input parameters to the neural net
are as follows:
- input dataset – complete path of the post-processed input dataset
- training percent – percentage of the dataset to be used for training
- maximum_iterations – Maximum number of iterations that your algorithm will run. This
parameter is used so that your program terminates in a reasonable time.
- number of hidden layers
- number of neurons in each hidden layer
For example, input parameters could be:
ds1 80 200 2 4 2

While coding the neural network, you can make the following assumptions:
- the activation function will be sigmoid
- you can use the backpropagation algorithm
- the training data will be randomly sampled from the dataset. The remaining will form the test
dataset
- you can use the mean square error as the error metric
- one iteration involves a forward and backward pass of the back propagation algorithm
- your algorithm will terminate when either the error becomes 0 or the max number of
iterations is reached.

