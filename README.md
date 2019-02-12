# Handwritten-digit-identification
Trained a neural network to identify handwritten digit

## Introduction
The purpose of this project is not to ,but give you a idea how to build and train a neural network

## About the Data
The dataset has a training set of 60,000 examples, and a test set of 10,000 examples.Each example is a 28x28 grayscale image. 

It is a good database for people who want to try learning techniques and pattern recognition methods on real-world data while spending minimal efforts on preprocessing and formatting. 

Members of the AI/ML/Data Science community love this dataset and use it as a benchmark to validate their algorithms. In fact, MNIST is often the first dataset researchers try. "If it doesn't work on MNIST, it won't work at all", they said. "Well, if it does work on MNIST, it may still fail on others."

Here's an example how the data looks 

![This is how it looks like](MNIST.jpg)

## Tools Used
* Torch
* [Torchvision](https://pypi.org/project/torchvision/0.1.8/)
* Numpy
* Matplotlib
* Collections

## Training Steps
1. Download datasets from [Torchvision](https://pypi.org/project/torchvision/0.1.8/)

2. Use Dataloader of Pytorch to load data,DataLoader can shuffle the data and accelerate training process

3. Build a network, choose a loss function and optimizer

4. Train the network

5. Use the trained network to identify digits from testing dataset

## Result

