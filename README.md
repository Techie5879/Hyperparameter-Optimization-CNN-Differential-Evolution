# Hyperparameter Optimization of CNN Using Differential Evolution Algorithm
This repository contains the code implementation for the Hyperparameter Optimization of Convolutional Neural Networks for Speech Command Recognition using Differential Evolution

## Introduction

### Differential Evolution:  
Differential Evolution (DE) is a population-based optimization algorithm and is a powerful as well as versatile evolutionary algorithm commonly used to solve optimization problems, especially in continuous domains.

DE belongs to the class of evolutionary algorithms that mimic the process of natural selection and evolution. Inspired by the principle of survival of the fittest, DE aims to iteratively improve a population of candidate solutions to find the optimal or near-optimal solution to a given problem.

### Dataset and Problem Statement:  
This implementation uses Differential Evolution based Hyperparameter Search for Convolutional Neural Networks for the Google Speech Commands dataset to optimize recognition of speech commands for 8 classes: "down", "go", "left", "no", "right", "stop", "up" and "yes".  
The approach is then compared to Optimization of CNN using Genetic Algorithm (GA) and performance of Pre-Trained Deep CNN (DCNN) Models on the same dataset.

## Libraries Used:
- Tensorflow (for CNN Model Architecture, Model Training, Pre-Trained models)
- Librosa (Audio Signal Processing)
- Numpy
- Sklearn (for metrics)
