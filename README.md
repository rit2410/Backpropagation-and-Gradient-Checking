# Backpropagation-and-Gradient-Checking

## Backpropagation 

1. It is a fundamental technique used in training neural networks to update model parameters (weights and biases) based on the calculated gradients of the loss function with respect to these parameters.
2. It involves two main phases: **the forward pass, where inputs are processed layer by layer to make predictions, and the backward pass, where the gradients are computed layer by layer in reverse order to update the parameters.**
3. Backpropagation enables the network to learn by iteratively adjusting its parameters to minimize the loss function, thus improving its performance on the task at hand.

## Gradient Checking

1. Gradient Checking is a **validation technique used to ensure that the gradients computed through backpropagation are accurate**.
2. It involves numerically approximating the gradients of the loss function with respect to the parameters using small perturbations, and then comparing these approximated gradients to the gradients obtained through backpropagation.
3. If the computed gradients closely match the numerical approximations, it indicates that the backpropagation process is working correctly and the model's gradients are being calculated accurately.
