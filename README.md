# AutoGrad: A Computational Graph for Gradient Backpropagation

The `Value` class is a simple Python implementation of a scalar-based computational graph node designed for gradient backpropagation. This class enables building and manipulating computational graphs while supporting operations such as addition, multiplication, power, activation functions, and more.

## Features

- **Scalars and Gradients**: Store scalar values and their gradients for backpropagation.
- **Automatic Differentiation**: Compute gradients using a backward pass with chain rule application.
- **Supported Operations**:
  - Addition, Subtraction, Multiplication, Division
  - Power operations
  - Activation functions like ReLU
  - Logarithm and Exponentiation
- **Chaining Operations**: Build complex computational graphs through operation chaining.
- **Customizable Backpropagation**: Define custom backward functions for new operations.
