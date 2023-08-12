# PyTorch Lightning

This repository contains a experiment conducted on the MNIST dataset using the PyTorch Lightning framework. The goal of this experiment is to demonstrate various techniques using PyTorch Lightning.


## Introduction

The MNIST dataset consists of handwritten digit images and their corresponding labels. PyTorch Lightning simplifies the training and evaluation process of deep learning models by providing a high-level interface. This repository showcases how to implement and experiment with different model architectures and techniques using PyTorch Lightning.

## Setup

To run the experiments, follow these steps:

1. Clone this repository:

   - `git clone https://github.com/bala1802/PyTorch-Lightning.git`
   - `cd PyTorch-Lightning`

2. Create a Virtual Environment

    - `conda create -n pytorch-lightning python=3.8`
    - `conda activate pytorch-lightning`

3. Install Packages
    
    - `pip install -r requirements.txt`

## About PyTorch Lightning

PyTorch Lightning is a high-level wrapper for PyTorch that streamlines the training and evaluation of deep learning models. It abstracts away the boilerplate code, providing automatic handling of GPU acceleration, distributed training, and more. With its modular design, it enables rapid experimentation and cleaner code, making it easier to focus on model development and research.

## Key Points

1. **Structured Abstraction**: PyTorch Lightning enforces a clear separation between the research aspects of model development and the engineering aspects of training. It provides predefined hooks and structure, reducing code duplication and making experiments more organized and readable.
2. **Simplified Training Loop**: The library abstracts away the traditional training loop, handling details such as data loading, validation, and testing. This streamlines the process, allowing researchers to focus on designing architectures and experimenting with hyperparameters.
3. **GPU and Distributed Training**: PyTorch Lightning automatically manages GPU acceleration and supports distributed training. By handling these complexities behind the scenes, it makes it easier to scale experiments across multiple GPUs or machines.
Reproducibility and Logging: It includes built-in support for automatic logging of metrics, hyperparameters, and visualizations to TensorBoard, making experiments more reproducible and trackable. This is essential for comparing results and understanding the impact of changes.
4. **Integration with Best Practices**: PyTorch Lightning integrates seamlessly with best practices in deep learning research, such as gradient accumulation, mixed-precision training, and model checkpoints. These integrations save time and ensure models are developed with state-of-the-art techniques.
