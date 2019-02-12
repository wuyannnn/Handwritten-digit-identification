# Handwritten-digit-identification
Trained a neural network to identify handwritten digit

## About the Data
The dataset has a training set of 60,000 examples, and a test set of 10,000 examples.It is a good database for people who want to try learning techniques and pattern recognition methods on real-world data while spending minimal efforts on preprocessing and formatting. 

![This is how it looks like](MNIST.jpg)

## Tools Used
* Torch
* [Torchvision](https://pypi.org/project/torchvision/0.1.8/)
* Numpy
* Matplotlib
* Collections

## Training Steps
1. Download datasets from [Torchvision](https://pypi.org/project/torchvision/0.1.8/)

2. Use Dataloader of Pytorch to load data,this can shuffle and accelerate training process

3. Build a network, choose a loss function and optimizer

4. Train the network

5. Use the trained network to identify digits from testing dataset
