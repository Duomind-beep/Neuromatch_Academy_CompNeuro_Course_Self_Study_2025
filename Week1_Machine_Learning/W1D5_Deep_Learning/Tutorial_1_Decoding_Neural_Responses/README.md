# Tutorial Objectives
In this tutorial, we'll use deep learning to decode stimulus information from the responses of sensory neurons. Specifically, we'll look at the activity of ~20,000 neurons in the mouse primary visual cortex responding to oriented gratings recorded in [this study](https://www.biorxiv.org/content/10.1101/679324v2.abstract). Our task will be to decode the orientation of the presented stimulus from the responses of the whole population of neurons. We could do this in a number of ways, but here we'll use deep learning.
* Build a deep feed-forward network using PyTorch
* Evaluate the network's outputs using PyTorch built-in loss functions
* Compute gradients of the loss with respect to each parameter of the network using automatic differentiation
* Implement gradient descent to optimize the network's parameters
