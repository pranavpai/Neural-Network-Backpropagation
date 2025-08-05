# Neural Network Backpropagation

![Python](https://img.shields.io/badge/python-3.6+-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![NumPy](https://img.shields.io/badge/NumPy-013243.svg?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Neural Networks](https://img.shields.io/badge/topic-Neural%20Networks-red.svg)
![Machine Learning](https://img.shields.io/badge/topic-Machine%20Learning-yellow.svg)

A hands-on implementation of neural network backpropagation from scratch, designed to train a network to approximate curve coordinates in 2D space.

## 📋 Description

This project implements a complete backpropagation algorithm for training a multi-layer neural network. The network learns to map a single input parameter (curve position from 0 to 1) to 2D coordinates, effectively learning to draw a curve.

### Network Architecture
- **Input Layer**: 1 neuron (curve position parameter)
- **Hidden Layer 1**: 6 neurons 
- **Hidden Layer 2**: 7 neurons
- **Output Layer**: 2 neurons (x, y coordinates)
- **Activation Function**: Logistic function (sigmoid)

## ✨ Features

- Complete backpropagation implementation with Jacobian calculations
- Layer-by-layer gradient computation (from output to input)
- Stochastic gradient descent optimization
- Interactive visualization of training progress
- Educational code structure with detailed comments

## 🛠️ Requirements

- Python 3.6+
- NumPy
- Matplotlib
- Jupyter Notebook

## 🚀 Usage

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook Backpropagation.ipynb
   ```

2. Run all cells sequentially to:
   - Initialize the neural network
   - Generate training data
   - Train the network using backpropagation
   - Visualize results

3. Experiment with different parameters:
   - Network size: `reset_network(n1, n2)`
   - Training iterations and learning rate
   - Noise levels

## 📁 Project Structure

```
├── Backpropagation.ipynb    # Main implementation notebook
├── README.md               # This file
└── LICENSE                # MIT License
```

## 🎯 Learning Objectives

- Understand backpropagation algorithm mechanics
- Implement gradient calculations for each layer
- Learn about Jacobian matrices in neural networks
- Practice with activation functions and cost functions
- Visualize neural network training dynamics

## 📈 Training Process

The network uses:
- **Cost Function**: Mean squared error between predicted and target coordinates
- **Optimization**: Stochastic gradient descent
- **Training Data**: Curve coordinates generated from parametric equations
- **Convergence**: Typically requires ~50,000 iterations

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
