# Neural_Network_From_Scratch
In this project, I build a neural network from scratch, implementing the forward pass and backpropagation through gradient calculations to create a functioning neural network trained on the MNIST dataset using only numpy. This is then compared to a Pytorch neural network trained on the same dataset

1. MNIST dataset is downloaded
2. Linear layer class is constructed, with forward and backward functions defined. 
3. ReLu activation function class is created
4. Softmax cross entropy layer is created, which calculates the cross entropy loss from the output of the softmax
5. Backward layer in the softmax class is created to backpropagate the calculated loss down to the linear layer using gradients
6. Method of finite differences is used to verify that the backpropagation is functioning as expected
7. Neural network is trained on a training loop
8. Validation loop is created to plot validation loss and error as training iterations and weight updates occur
9. PyTorch neural network is constructed as a comparison to the pure numpy neural network
