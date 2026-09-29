In this lab we build a small neural network, a multi-layer perceptron (MLP), using nothing but NumPy. We will write every step ourselves:
the forward pass: how the network turns inputs into a prediction,
the loss: a number that tells us how wrong the prediction is,
the backward pass (backpropagation): how much each weight is responsible for the error,
the update: changing each weight a little so that the error becomes smaller.
Libraries such as PyTorch do steps 3 and 4 automatically with loss.backward() and optimizer.step(). Doing them once by hand is the best way to understand what those two lines really do.
