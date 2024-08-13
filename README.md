Overview

This repository provides a hands-on approach to understanding backpropagation and gradient computation using Micrograd, a minimalistic educational deep learning library created by Andrej Karpathy. Through these exercises, you’ll explore the core concepts of automatic differentiation, computational graphs, and how frameworks like PyTorch handle gradient-based optimization.


Features

Custom Value Class

    Implement a Value class that forms the backbone of a computational graph, enabling the execution of arithmetic operations and automatic differentiation.
    Understand how each operation affects the computational graph and how gradients are propagated through it.

Finite Difference Approximation

    Explore the numerical method of approximating gradients using finite difference. This method involves perturbing each input slightly and observing the resulting change in the output, providing an intuitive grasp of how gradients are computed.
    Implement and compare this approach with analytical gradients to see the accuracy and limitations of numerical approximation.

Symmetric Derivatives

    Delve into the concept of symmetric derivatives, an improvement over simple finite difference approximations. This method averages the forward and backward differences to provide a more accurate gradient estimation.
    Implement symmetric derivative calculations and understand their role in reducing numerical errors during gradient estimation.

Softmax and Negative Log-Likelihood

    Implement the softmax function, a crucial operation in many classification tasks, converting logits into probabilities.
    Compute the negative log-likelihood loss, commonly used in classification, to understand how to penalize incorrect predictions.

Gradient Verification with PyTorch

    Verify the manually computed gradients using PyTorch, ensuring that your implementation matches the industry-standard approach. This step is crucial for understanding the correctness of your backpropagation implementation.
